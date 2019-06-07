---
layout: post
title: Testing Soft and Hard Homogenization Protocol
date: '2019-06-06'
categories: Protocols
tags: RNA, DNA, Soft homogenization, Hard homogenization, extraction
projects: Holobiont Integration
---

# Soft and Hard Homogenization Protocol testing

20190606 E.S.

Testing the soft and hard homogenization protocol on extra molecular samples from the recovery time period of the Holobiont Integration project. 2 *M. capitata* and 2 *P. acuta* fragments were randomly chosen.

Original samples:

| ORIGIN | Site.Name       | POINT | SITE.ID | Species   | COLLECT.DATE | PLUG.ID | TANK# | TREATMENT | ANALYSIS  | TIME  | TIME POINT | SAMPLING.DATE | Dead.Alive | NOTES                        | Sample Location   | Shipment Date | Lab Work                     | Lab Work by | Lab Work Date |
|--------|-----------------|-------|---------|-----------|--------------|---------|-------|-----------|-----------|-------|------------|---------------|------------|------------------------------|-------------------|---------------|------------------------------|-------------|---------------|
| SITE 4 | Reef.11.13      | 6     | P60     | Pacuta    | 20180907     | 1431    | 6     | ATAC      | Molecular | 11:24 | 11         | 20181215      | Alive      | In Tank 6 20181118; off plug | In Transit to URI | 20190206      | Soft and hard homogenization | ES          | 20190606      |
| SITE 1 | Lilipuna.Fringe | 6     | M54     | Mcapitata | 20180908     | 1591    | 8     | ATAC      | Molecular | 10:12 | 11         | 20181215      | Alive      | In Tank 8 20181118           | In Transit to URI | 20190206      | Soft and hard homogenization | ES          | 20190606      |
| SITE 3 | Reef.18         | 5     | M45     | Mcapitata | 20180910     | 2309    | 6     | ATAC      | Molecular | 11:28 | 11         | 20181215      | Alive      | In Tank 6 20181118; off plug | In Transit to URI | 20190206      | Soft and hard homogenization | ES          | 20190606      |
| SITE 3 | Reef.18         | 8     | P72     | Pacuta    | 20180910     | 2364    | 6     | ATAC      | Molecular | 11:27 | 11         | 20181215      | Alive      | In Tank 6 20181118           | In Transit to URI | 20190206      | Soft and hard homogenization | ES          | 20190606      |

General notes:  
- Proteinase K buffer and Proteinase K added after bead beating steps.  
- Vortexing for two minutes was more than enough time. The *P. acuta* tissue came off quicker than *M. capitata*. This might cause problems later in the protocol. Maybe less beads or more fragment pieces?  
- Almost all of the tissue from fragment 1431 came off during the "soft" homogenization step.  
- Half of the beads from bead bug machine tubes were used.  
- Tissue Lyser was broken, so bead bug was used for the "hard" homogenization step instead. Run at 400 speed and 30 seconds.  
- Both homogenization steps got at least 500 uL of sample.  
- 500 uL of shield used instead of 1000 uL for the "hard" homogenization step.  
- After hard homogenization, not all of the tissue from the *M. capitata* came off the skeleton, but the liquid was dark brown.  
- 30 uL of Proteinase K Buffer, and 15 uL of Proteinase K used.  
- Heating started at 12:55, ended at 2:25.  

Calculations:  
DNAse I  
- 75 uL buffer x 8 samples = 600 uL buffer  
- 5 uL DNAse I x 8 samples = 40 uL DNAse I

Qubit Master Mix (x2 for DNA and RNA)  
- 8 samples + 2 standards + 0.2% error = 10.2 uL of Quant-IT Reagent  
- 199 x 10.2 = 2,029.8 uL buffer

2 standards: 190 uL Master Mix + 10 uL standard  
16 samples: 199 uL Master Mix + 1 uL sample  

15 minute incubation started at 3:44  
- Gel made and hardening at 3:58  
- Re-aliquoted fragment 1591 hard and soft DNA and RNA tubes

Qubit Results  
dsDNA broad range

| DNA(ug/uL)    | Trial 1   | Trial 2 | Avg |
|------------|-----------|---------|-------|
| Standard 1 | 174.13    | NA      | NA    |
| Standard 2 | 18,408.70 | NA      | NA    |
| 1591 Hard  | 109       | 107     | 108   |
| 1591 Soft  | 54.4      | 53.8    | 54.1  |
| 1431 Hard  | 130       | 130     | 130   |
| 1431 Soft  | 193       | 192     | 192.5 |
| 2309 Hard  | 65.8      | 65.2    | 65.5  |
| 2309 Soft  | 47.6      | 47.2    | 47.4  |
| 2364 Hard  | 199       | 198     | 198.5 |
| 2364 Soft  | 55.4      | 54.8    | 55.1  |

RNA broad range

| RNA  (ug/uL)      | Trial 1   | Trial 2 | Avg  |
|------------|-----------|---------|------|
| Standard 1 | 396.31    | NA      | NA   |
| Standard 2 | 10,506.90 | NA      | NA   |
| 1591 Hard  | 66.2      | 66.2    | 66.2 |
| 1591 Soft  | 73.2      | 73      | 73.1 |
| 1431 Hard  | 158       | 158     | 158  |
| 1431 Soft  | 274       | 274     | 274  |
| 2309 Hard  | 75.6      | 75.4    | 75.5 |
| 2309 Soft  | 32.4      | 32.4    | 32.4 |
| 2364 Hard  | 193       | 193     | 193  |
| 2364 Soft  | 202       | 202     | 202  |

Gel Electrophoresis:
- 1.5% agarose gel  
- Run at 100V for 45 minutes, start 6:00 end 6:45  
- Ladder:  
- Dye:  
- 4 uL ladder + 1 uL dye, 5 uL sample + 1 uL dye  


Sample order: Ladder, 2364 Hard, 2364 Soft, 2309 Hard, 2309 Soft, 1431 Hard, 1431 Soft, 1591 Hard, 1591 Soft
![Image](https://github.com/emmastrand/EmmaStrand_Notebook/blob/master/images/IMG_8044.jpg?raw=true)

TapeStation Results:  
- Thermocycler (rna denature program) start 6:15 end 6:21  
- TapeStation start 6:28 end 6:38  
- Ladder: 

| Coral ID | Tape Station ID |   RIN^e  |
|-----------------|-------|-----|
| Ladder          | A1    | NA  |
| 1591 Hard       | B1    | 3.3 |
| 1591 Soft       | C1    | 4   |
| 1431 Hard       | D1    | 7   |
| 1431 Soft       | E1    | 7.7 |
| 2309 Hard       | F1    | 7.1 |
| 2309 Soft       | G1    | 8.3 |
| 2364 Hard       | H1    | 4.1 |
| 2364 Soft       | A2    | 6.9 |

[Link to report](https://github.com/emmastrand/EmmaStrand_Notebook/blob/master/TapeStation/2019-06-06%20-%2018.25.53.pdf)
