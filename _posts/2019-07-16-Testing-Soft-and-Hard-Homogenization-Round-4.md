---
layout: post
title: Testing Soft and Hard Homogenization Round 4
date: '2019-07-16'
categories: Processing
tags: RNA, DNA, coral, extractions, soft and hard homogenization
projects: Holobiont Integration
---

20190716 E. Strand

Testing the soft and hard homogenization protocol on extra molecular samples from the December recovery time period of the Holobiont Integration project. 2 *M. capitata* and 2 *P. acuta* fragments were randomly chosen from ATAC treatment 20181215. These four fragments were used on 20190715 and 20190716.

Changes for round 4:  
- No heat to lyse step because the heating might be contributing to the RNA degradation  
- just 1 fragment clipping because the RNA DNA shield might be overloaded with more than one clipping

| Extraction # | Coral ID | Species     | Homogenization |
|--------------|----------|-------------|----------------|
| 1            | 1123     | Montipora   | Soft           |
| 2            | 1123     | Montipora   | Hard           |
| 3            | 1769     | Montipora   | Soft           |
| 4            | 1769     | Montipora   | Hard           |
| 5            | 1056     | Pocillopora | Soft           |
| 6            | 1056     | Pocillopora | Hard           |
| 7            | 1607     | Pocillopora | Soft           |
| 8            | 1607     | Pocillopora | Hard           |

DNA RNA Extraction Protocol found [here](https://github.com/emmastrand/EmmaStrand_Notebook/blob/master/_posts/2019-05-31-Zymo-Duet-RNA-DNA-Extraction-Protocol.md).

Before homogenization steps:  

![Before](https://github.com/emmastrand/EmmaStrand_Notebook/blob/master/images/20190716_before.JPG?raw=true)

After soft homogenization:  

![After_soft](https://github.com/emmastrand/EmmaStrand_Notebook/blob/master/images/20190716_soft.JPG?raw=true)

After hard homogenization:  

![After_hard](https://github.com/emmastrand/EmmaStrand_Notebook/blob/master/images/20190716_hard.JPG?raw=true)

500 µl of DNA RNA shield accidentally added to the soft homogenization tubes. The supernatant taken from the soft homogenization step instead of adding the shield to the tube with the coral fragment clippings.

Extraction steps: start 10:00 end 12:06. 8 samples takes about two hours.  

1056 soft DNA final tube lost some liquid.

DNAse I Master Mix Calculations:  
- 75 µl x 8 samples = 600 µl buffer  
- 5 µl DNase I x 8 samples = 40 µl DNase I enzyme

[Qubit](https://github.com/emmastrand/EmmaStrand_Notebook/blob/master/_posts/2019-05-31-Qubit-Protocol.md) Results:

Master Mix Calculations:  
- 8 samples + 2 standards + 0.2% error = 10.2 µl Quant-IT Reagent  
- 199 * 10.2 = 2,029.8 µl Qubit buffer

| DNA (ng/μl)        |                  |      |      |
|------------|------------------|------|------|
| Standard 1 | 176.27           |      |      |
| Standard 2 | 20135.99         |      |      |
| 1          | 1132 Mcap soft   | 20.8 | 20.8 |
| 2          | 1132 Mcap hard   | 20.8 | 20.6 |
| 3          | 1769 Mcap soft   | 27   | 26.8 |
| 4          | 1769 Mcap hard   | 28   | 28   |
| 5          | 1056 Pacuta soft | 39.4 | 39.4 |
| 6          | 1056 Pacuta hard | 54   | 53.8 |
| 7          | 1607 Pacuta soft | 18.6 | 18.5 |
| 8          | 1607 Pacuta hard | 17.4 | 17.3 |

| RNA (ng/μl)        |                  |      |      |
|------------|------------------|------|------|
| Standard 1 | 393.16           |      |      |
| Standard 2 | 10592.52         |      |      |
| 1          | 1132 Mcap soft   | 11.8 | 11.8 |
| 2          | 1132 Mcap hard   | 10.6 | 10.6 |
| 3          | 1769 Mcap soft   | 16.6 | 16.6 |
| 4          | 1769 Mcap hard   | 20.4 | 20.4 |
| 5          | 1056 Pacuta soft | 34.2 | 34.2 |
| 6          | 1056 Pacuta hard | 47.2 | 47.2 |
| 7          | 1607 Pacuta soft | 27.8 | 27.8 |
| 8          | 1607 Pacuta hard | 22.8 | 22.8 |

[Gel Electrophoresis](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/Gel-Protocol/):  
- 100V for 45 minutes, start 12:47 end 13:32  
- 75 μl TAE buffer + 0.75 g agarose + 5 μl of [Biotium gel RED gel stain](https://biotium.com/technology/nucleic-acid-gel-stains/gelred-gelgreen-dna-gel-stains/?keyword=dna%20gel%20electrophoresis&creative=262626170330&gclid=EAIaIQobChMIsIKv5va34wIVzICfCh1BowDnEAAYASAAEgKjK_D_BwE) to make a 1.5% gel.  
- 5 μl samples + 1 μl 6x purple loading dye  
- 4 μl [GeneRuler 1 kb Plus DNA ladder](https://github.com/emmastrand/EmmaStrand_Notebook/blob/master/images/GeneRuler_1kb_Plus_DNALadder_250ug_UG.bmp-650.jpg?raw=true) + 1 μl 6x purple loading dye

Gel order: Ladder, 1-8

![Gel20190716](https://github.com/emmastrand/EmmaStrand_Notebook/blob/master/images/20190716_gel.JPG?raw=true)

[TapeStation](https://github.com/emmastrand/EmmaStrand_Notebook/blob/master/_posts/2019-05-31-TapeStation-Protocol.md) Results:

| Extraction ID | Coral ID         | RIN^e |
|---------------|------------------|-------|
| 1             | 1132 Mcap soft   | 6.1   |
| 2             | 1132 Mcap hard   | **   |
| 3             | 1769 Mcap soft   | 7.7   |
| 4             | 1769 Mcap hard   | 8.2   |
| 5             | 1056 Pacuta soft | 6.9   |
| 6             | 1056 Pacuta hard | 7.1     |
| 7             | 1607 Pacuta soft | 6.3     |
| 8             | 1607 Pacuta hard | 6.0   |

** Concentration too low for TapeStation to detect.

TapeStation re-done because samples were out of range.

[Link to the first 20190716 report](https://github.com/emmastrand/EmmaStrand_Notebook/blob/master/TapeStation/2019-07-16%20-%2013.24.12.pdf)  
[Link to the second 20190716 report](https://github.com/emmastrand/EmmaStrand_Notebook/blob/master/TapeStation/2019-07-16%20-%2014.11.01.pdf)  
[Link to Agilent 4200 TapeStation System](https://www.agilent.com/cs/library/technicaloverviews/public/5991-6616EN.pdf)  

- Thermocycler (rna denature program): 3 minutes at 72 &deg;C, 2 minutes at 4 &deg;C, hold at 4 &deg;C.  
- TapeStation start 14:10 end 14:20  
- Ladder: [Agilent RNA screentape ladder](https://www.agilent.com/en/product/automated-electrophoresis/tapestation-systems/tapestation-rna-screentape-reagents/rna-screentape-analysis-228268)
