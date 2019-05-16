# Creating a "browse by" category

Author: Emma L. Strand  
Date: 20190515]

Following instructions are to add a "project" category.

### 1. Select _layouts folder 

Steps completed on github.

- Select `default.html` document  
- Click the "edit this file" option 

Each "browse by" category has the following lines: 

```
or <a title="The complete archive of
     {{ site.name }}'s Notebook by tag"
     href="{{ site.url}}{{site.baseurl}}/tagview">tag</a>
```
-  Find `href="{{ site.url}}{{site.baseurl}}/tagview">tag</a>` on line 43 
-  After the above line, add `or <a title="The complete archive of
     {{ site.name }}'s Notebook by project`. This will extend to line 44.
- Click enter 
- On line 45 add `href="{{ site.url}}{{site.baseurl}}/projectview">project</a>`
- Click the green "Commit changes" button

### 2. Create an archive by project markdown file 

Steps completed in folder and terminal.

- Copy the `archivebycategory.md` file 
- Rename this file to `archivebyproject.md` 
- Open this file in markdown editor 
- Change `Post by Category` under "title" to `Post by Project` 
- Change `/categoryview/` under "permalink" to `/projectview/` 
- Change `archivebycategory` under "active" to `/archivebyproject` 
- Change `{% assign tags = site.categories | sort %}` on the first line after the table ends to `{% assign tags = site.projects | sort %}`
- Change `{% for post in sorted_posts %}{%if post.categories contains tag[0]%}` to `{% for post in sorted_posts %}{%if post.projects contains tag[0]%}`

### 3. Edit the post bash script 

Steps completed on github.

- Select _posts folder 
- Click on `post_template.sh` file 
- Click the "edit this file" option
- In the `# Set variables` section, add a new line underneath line 19 `"TAGS="tags: "` that reads `PROJECTS="projects: "`
- In the `# Ask user for input` section, each "browse by" category has the following:

```
echo "Enter tags: include []"
read PHRASE3
echo "You entered $PHRASE3"
```
- Add the following underneath the tags code (line 31-33)

```
echo "Enter projects: include []" 
read PHRASE4
echo "You entered $PHRASE4"
```

- In line 47 `# Writes contents to NEW_MD_FILE`, insert `"$PROJECTS" "$PHRASE4"` after `"$TAGS" "$PHRASE3"`. The line should read `printf "%s\n%s\n%s%s\n%s'%s'\n%s%s\n%s%s\n%s%s\n" "$MD_LINE" "$LAYOUT" "$TITLE" "$PHRASE" "$DATE_LINE" "$POST_DATE" "$CATEGORIES" "$PHRASE2" "$TAGS" "$PHRASE3" "$PROJECTS" "$PHRASE4" "$MD_LINE" >> \`

- Click the green "Commit changes" button