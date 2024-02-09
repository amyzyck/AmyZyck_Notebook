---
layout: post
title: RISG KAPA Stranded mRNA Seq Prep
date: '2024-02-09'
categories: Processing, Protocols
tags: [Crassostrea virginica, oyster, KAPA, RNA, mRNA, Library Prep]
projects: [Rhode Island Sea Grant]
---

## KAPA Stranded mRNA Seq Prep of Larval Oyster Samples 

Using [KAPA Stranded mRNA Seq Kit with mRNA Capture Beads](https://sequencing.roche.com/us/en/products/group/kapa-stranded-rna-seq-kits.html) 

Following the [KAPA mRNA HyperPrep Kit Protocol](https://genome.med.harvard.edu/documents/libraryPrep/KAPAmRNAHyperPrepProtocol.pdf) using half volumes. 

**Time to Completion: ~12 hours (includes pooling RNA samples at beginning and OC at the end)**

### Sample Preparation

Prior to bead capture, the three replicate RNA samples for each treatment were pooled, with timepoint and Blocks kept separate. For mRNA Seq Prep, the desired starting input was 1200 ng of RNA concentrated in 25 μL. 

Ten of the thirty capture pools needed to be vacufuged into a smaller volume prior to mRNA Seq Prep. Steps for vacufuging of these samples can be accessed [here](https://amyzyck.github.io/AmyZyck_Notebook/RISG-Vacufuge-of-RNA-Samples/).

All calculations and notes for pooling RNA samples can be accessed [here](https://docs.google.com/spreadsheets/d/1jGcuh2gzTWEF-I5Q9s6QY_uEYRuJ7xy2vUGYlyYpWAA/edit?usp=sharing).

- Pull samples out of -80 freezer and thaw on ice 
- Perform any necessary pooling
- Pipette pooled samples to mix and spin down 

### mRNA Bead Capture

- Pull bead kit out of fridge and warm to room temperature
- Gently invert bead bottle and pipette to suspend beads 
- Calculate number of beads needed for samples
    - 26.25 μL x # of samples 
    - *For 10 samples, 263 μL of beads are needed*
- Pipette the calculated volume of beads (263 μL) into a 1.5 mL tube and put tube on large magnet stand 
- Remove liquid when clear, being careful not to disturb the beads
- Add the same volume (263 μL) of Bead Binding Buffer and resuspend beads off of magnet
- Put tube back on magnet, remove liquid when clear (as much as possible)
- Add the same volume (263 μL) of Bead Binding Buffer and resuspend beads off of magnet
- Put tube back on magnet, remove liquid when clear (as much as possible)
- Add the same volume (263 μL) of Bead Binding Buffer and resuspend beads off of magnet
- Add 25 μL of the resuspended mRNA beads to each RNA sample and pipette to mix
- Thermocycler 1st mRNA Capture program 
- After thermocycler program, place tubes on magnet and discard liquid when clear 
- Remove tubes from magnet and resuspend beads in 100 μL of Bead Wash Buffer
- Place tubes on magnet and remove liquid when clear 
- Remove tubes from magnet and resupend beads in 25 μL of RNAse-free water
- Thermocycler 2nd mRNA Capture program
- After thermocycler program, add 25 μL of Bead Binding Buffer and pipette to mix
- Incubate tubes at 20 degrees C for 5 minutes in thermocycler (program exists)
- Make 1X Fragment, Prime, and Elute (FPE) Buffer on ice 
    - Nuclease-free water: 5.5 μL x # of samples
    - 2X FPE Buffer: 5.5 μL x # of samples
- After incubation, place tubes on magnet and discard liquid when clear
- Remove tubes from magnet and resuspend beads in 100 μL of Bead Wash Buffer
- Place tubes on magnet and discard liquid when clear 
- Remove tubes from magnet and resuspend beads in 11 μL of 1X FPE Buffer
- Thermocycler RNA Fragmentation program (7 minutes at 94 degrees C)

### First and Second Strand Synthesis

- Make 1st Strand cDNA Synthesis mix on ice:
    - 1st Strand Synthesis Buffer: 5.5 μL x # of samples
    - KAPA script: 0.5 μL x # of samples 
- After thermocycler program, IMMEDIATELY put tubes on magnet
- Transfer 10 μL of clear liquid to new PCR tubes on ice
- Add 5 μL of 1st Strand Synthesis mix to each sample and pipette to mix
- Thermocycler 1st Strand Synthesis program (~40 minutes)
- Make 2nd Strand Synthesis mix on ice:
    - 2nd Strand Marking Buffer: 15.5 μL x # of samples
    - 2nd Strand Enzyme: 1 μL x # of samples
- After thermocycler program, place tubes on ice
- Add 15 μL of 2nd Strand Synthesis mix to each sample and pipette to mix
- Thermocycler 2nd Strand Synthesis program (~1 hour)
- Take KAPA Pure Beads out of fridge to warm to room temperature (light sensitive)
- Make 80% EtOH
- Take tubes out of thermocycler and add 54 μL of KAPA Pure Beads to each tube and pipette to mix
- Incubate on shaker for 15 minutes at 300 rpm and at room temperature
- Make A-Tailing Immediately mix on ice:
    - Nuclease-free water: 12 μL x # of samples
    - 10X A-Tailing Buffer: 1.5 μL x # of samples
    - A-Tailing Enzyme: 1.5 μL x # of samples
- After 15 minutes on shaker, perform normal bead clean steps 
- Resuspend beads in 15 μL of A-Tailing Immediately mix 
- Thermocycler A-Tailing program (~1 hour)

### Adapter Ligation

- Make Adapter Ligation mix on ice:
    - Nuclease-free water: 8 μL x # of samples
    - Ligation Buffer: 7 μL x # of samples
    - DNA Ligase: 2.5 μL x # of samples (pull out 30 minutes before use)
- Make 700 nM working stock of SAIIv2 adapter - we have a 1.5 μM stock in the freezer
    - Total volume needed of diluted adapter: 2.5 μL x # of samples
    - Volume of SAIIv2 adapter (700nM/1500 nM) x 2.5 μL x # of samples
    - Fill remaining volume with nuclease-free water
- After thermocycler program, add 17.5 μL of Ligation mix and 2.5 μL of SAIIv2 (700  nM) to each sample on ice and pipette to mix
- Place tubes on shaker at 300 rpm at room temperature for 30 minutes
- After 30 minute incubation, add 35 μL of room temperature PEG to each sample and pipette to mix
- Perform normal bead clean steps
- Resuspend beads in 25 μL of 10 mM Tris HCl pH 8.0
- Add 25 μL of room temperature PEG to each sample and pipette to mix
- Perform normal bead clean steps 
- Resuspend beads in 11 μL of 10 mM Tris HCl pH 8.0
- Transfer 10 μL of sample to new PCR strip tubes

### Library Amplification

- Set up amplification with KAPA HiFi HotStart Ready Mix (HSRM) and index primer pairs
    - We use custom index primers 
    - *I used a 10 μM working stock of index primers, HOWEVER it is recommended that a 20 μM stock is used to maximize amplification* 
    - Index primer pair combinations were chosen to multiplex cDNA libraries in 3 probe pools (separate pools for each Block)
    - Specific index primers used for each sample can be accessed [here](https://docs.google.com/spreadsheets/d/1jGcuh2gzTWEF-I5Q9s6QY_uEYRuJ7xy2vUGYlyYpWAA/edit?usp=sharing)
- Combine 12.5 μL HSRM and 1.25 μL of each index primer into PCR tubes on ice
- Combine the 10 μL of adapter-ligated cDNA sample with 15 μL of the appropriate library amplification mix 
- Vortex and spin down
- Thermocycler PCR 12 program (~30 minutes)
- After PCR program, perform 1X bead clean 
    - Add 25 μL of KAPA Pure Beads
    - Resuspend and elute beads in 22 μL of 10 mM Tris HCl pH 8.0
- Transfer liquid to new PCR tubes 

*Because I used a 10 μM stock of the library amplificatiton index primers, the cDNA library concentrations were too small (less than 10 ng/μL). I peformed an additonal 6 cycle PCR amplification to increase number of libraries. Because libraries are already completed, I can use the Illumina universal primers for the re-amplification.*

- Combine 25 μL of HSRM and 5 μL of Illumin Primer mix
- Add 30 μL of amplification mix to the 20 μL sample
- Thermocycler PCR 6 program 
- Peform 1X bead clean
    - Add 50 μL of KAPA Pure Beads
    - Resuspend and elute in 22 μL of 10 mM Tris HCl pH 8.0
- Transfer all liquid to final PCR tube

#### Quality Control Check 

**Qubit**
- cDNA library concentrations are checked using the Biotium [dsDNA Broad Range](https://biotium.com/wp-content/uploads/2017/12/PI-31069.pdf) quantitation kit
- Final cDNA library concentrations (ng/μL) can be accessed [here](https://docs.google.com/spreadsheets/d/1jGcuh2gzTWEF-I5Q9s6QY_uEYRuJ7xy2vUGYlyYpWAA/edit?usp=sharing)

**TapeStation**
- cDNA libraries are checked using the [D5000 ScreenTape Assay](https://www.agilent.com/cs/library/usermanuals/public/ScreenTape_D5000_QG.pdf)
- Sample TapeStation report can be accessed [here](https://drive.google.com/file/d/1zPisxY_qLmG7QU8WpjD2vXR5HGQov6La/view?usp=sharing)