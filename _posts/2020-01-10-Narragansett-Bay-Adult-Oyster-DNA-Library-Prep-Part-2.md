---
layout: post
title: Narragansett Bay Adult Oyster DNA Library Prep Part 2
date: '2020-01-10'
categories: Processing, Protocols
tags: [Narragansett Bay, Crassostrea virginica, DNA, Library Prep]
projects: [Narragansett Bay]
---

### DNA Library Prep for NB Adult Oyster EecSeq - 14 Samples

***Initial bead cleanup was performed on Oct. 21, 2019 and library prep was performed on Oct. 28, 2019.***

Using the [KAPA HyperPrep DNA Library Prep Kit](https://sequencing.roche.com/en-us/products-solutions/by-category/library-preparation/dna-library-preparation/kapa-hyperprep.html) on 14 DNA samples in 10 mM Tris HCl pH 8 containing 500 ng from the first 50 samples of the NB adult oyster experiment.

Previously, all samples were sonicated to 150 bp following the [QSonica protocol](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/Qsonica/)- instructions can be found [here](https://amyzyck.github.io/AmyZyck_Notebook/Narragansett-Bay-Adult-Oyster-DNA-Sonication-Part-1/).

***A 1.8X bead cleanup was performed to concentrate 500 ng of DNA in 25 μl before library prep:***

- _Made fresh 80% EtOH_
- _Took KAPA Pure Beads out of fridge beforehand to warm to room temp_
- Vortex and spin down DNA samples
- Added 90 μl (1.8 x 50 μl) of KAPA Pure Beads to each sample and pipette up and down 10 times to mix (_avoid bubbles_)
- Placed tubes on shaker at room temp for 15 minutes - shaker set to 200 rpm's
- After 15 minute incubation, placed tubes on magnet plate and removed supernatant from tubes when it was fully clear not disturbing the beads
- Added 200 μl of 80% EtOH to each tube while still the magnet not disturbing the beads
- Removed supernatant from each tube on the magnet plate without disturbing the beads
- Added 200 μl of 80% EtOH to each tube while still the magnet not disturbing the beads
- Removed ALL the supernatant from each tube on the magnet plate without disturbing the beads. Extra EtOH blobs were removed with p20 pipette tips
- Resuspended beads in 25 μl of 10 mM Tris HCl pH 8 and incubated tubes on shaker at room temp for 5 minutes
- Placed tubes on magnet plate and transferred supernatant when clear to new labeled PCR strip tubes

#### End Repair and A-tailing

- Prepared end repair and a-tailing master mix:
_(should have multiplied by 15 instead of 14 to account for pipetting error)_
  - ERAT buffer: 3.5 μl * 14 = 49 μl
  - ERAT enzyme: 1.5 μl * 14 = 21 μl
- In the 14 PCR strip tubes containing the 25 μl of 500 ng sheared DNA, added 5 μl of ERAT master mix
- Vortexed and spun down
- Placed samples in thermocycler A-tailing program in JONP login - program runs for ~ 1 hour

#### Adapter Ligation

***Working adapter stocks 1-7, and 9-12 were diluted on Oct. 10, 2019; working adapter stock 8 was diluted on Oct. 21, 2019.*** Dilution was completed as followed:

- In new PCR strip tubes, added 20 μl of previously made annealed adapter stocks
- Added 20 μl of Nuclease free water to annealed adapter stocks for ***40 μl total of 20 μM adapter stocks***


- Prepared adapter ligation master mix:
_(should have multiplied by 15.5 instead of 14.5 to account for more pipetting error)_
  - Ligation buffer: 15 μl * 14.5 = 217.5 μl
  - DNA ligase: 5 μl * 14.5 = 72.5 μl
  - Nuclease free water: 2.5 μl * 14.5 = 36.3 μl
- Added 22.5 μl of ligation master mix and appropriately planned adapters to each sample. _Adapters were added last to minimize adapter-adapter ligation_.

|Sample|LMM|Adapter|
|---|---|---|
|1.3|22.5μl|2.5μl 3|
|1.5|22.5μl|2.5μl 5|
|2.7|22.5μl|2.5μl 5|
|2.9|22.5μl|2.5μl 7|
|2.10|22.5μl|2.5μl 8|
|3.4|22.5μl|2.5μl 12|
|3.6|22.5μl|2.5μl 2|
|3.10|22.5μl|2.5μl 6|
|4.1|22.5μl|2.5μl 7|
|4.3|22.5μl|2.5μl 9|
|4.10|22.5μl|2.5μl 4|
|5.4|22.5μl|2.5μl 8|
|5.7|22.5μl|2.5μl 11|
|5.9|22.5μl|2.5μl 1|

- Pipetted up and down to mix - pipette set to 50 μl
  - spin down
- Incubated samples on shaker at room temp for 1 hour

#### 0.8X Cleanup

- After incubation, added 44 μl of KAPA pure beads to each sample and pipetted up and down 10 times to mix (_avoid bubbles_)
- Placed tubes on shaker at room temp for 15 minutes
- Placed tubes on magnet plate and removed supernatant from tubes when it was fully clear not disturbing the beads
- Added 200 μl of 80% EtOH to each tube while still the magnet not disturbing the beads
- Removed supernatant from each tube on the magnet plate without disturbing the beads
- Added 200 μl of 80% EtOH to each tube while still the magnet not disturbing the beads
- Removed ALL the supernatant from each tube on the magnet plate without disturbing the beads. Extra EtOH blobs were removed with p20 pipette tips
- Resuspended beads in 12.5 μl 10 mM Tris HCl pH 8 and incubated tubes on shaker for 5 minutes
- Placed tubes back onto the magnet plate and removed supernatant when clear to new labeled PCR strip tubes

#### Library Amplification

- Every 5 samples get a different index primer pair for amplification. For these 14 samples, 8 different master mixes were made:
- Amp MM A - Samples 1.3 & 1.5
  - 12.5 μl HotStart Ready mix * 2.2 = 27.5 μl
  - 1.25 μl 501 primer * 2.2 = 2.75 μl
  - 1.25 μl 701 primer * 2.2 = 2.75 μl
- Amp MM B - Samples 2.7, 2.9, & 2.10
  - 12.5 μl HotStart Ready mix * 3.2 = 40 μl
  - 1.25 μl 504 primer * 3.2 = 4 μl
  - 1.25 μl 704 primer * 3.2 = 4 μl
- Amp MM C - Sample 3.4
  - 12.5 μl HotStart Ready mix
  - 1.25 μl 505 primer
  - 1.25 μl 705 primer
- Amp MM D - Samples 3.6 & 3.10
  - 12.5 μl HotStart Ready mix * 2.2 = 27.5 μl
  - 1.25 μl 506 primer * 2.2 = 2.75 μl
  - 1.25 μl 706 primer * 2.2 = 2.75 μl
- Amp MM E - Samples 4.1 & 4.3
  - 12.5 μl HotStart Ready mix * 2.2 = 27.5 μl
  - 1.25 μl 507 primer * 2.2 = 2.75 μl
  - 1.25 μl 707 primer * 2.2 = 2.75 μl
- Amp MM F - Sample 4.10
  - 12.5 μl HotStart Ready mix
  - 1.25 μl 508 primer
  - 1.25 μl 708 primer
- Amp MM G - Sample 5.4
  - 12.5 μl HotStart Ready mix
  - 1.25 μl 509 primer
  - 1.25 μl 709 primer
- Amp MM H - Samples 5.7 & 5.9
  - 12.5 μl HotStart Ready mix * 2.2 = 27.5 μl
  - 1.25 μl 510 primer * 2.2 = 2.75 μl
  - 1.25 μl 710 primer * 2.2 = 2.75 μl
- Prepared new PCR tubes for the amplification with the following:

|Sample|volume adapter added DNA of sample|volume of Amp MM|
|---|----|----|
|1.3|10μl|15μl Amp MM A|
|1.5|10μl|15μl Amp MM A|
|2.7|10μl|15μl Amp MM B|
|2.9|10μl|15μl Amp MM B|
|2.10|10μl|15μl Amp MM B|
|3.4|10μl|15μl Amp MM C|
|3.6|10μl|15μl Amp MM D|
|3.10|10μl|15μl Amp MM D|
|4.1|10μl|15μl Amp MM E|
|4.3|10μl|15μl Amp MM E|
|4.10|10μl|15μl Amp MM F|
|5.4|10μl|15μl Amp MM G|
|5.7|10μl|15μl Amp MM H|
|5.9|10μl|15μl Amp MM H|

- Vortexed and spun down
- Placed samples in the thermocycler Genomic PCR program

#### 1X Cleanup

- After PCR, added 25 μl of KAPA pure beads to each sample and pipetted up and down 10 times to mix (_avoid bubbles_)
- Placed tubes on shaker at room temp for 15 minutes
- Placed tubes on magnet plate and removed supernatant from tubes when it was fully clear not disturbing the beads
- Added 200 μl of 80% EtOH to each tube while still the magnet not disturbing the beads
- Removed supernatant from each tube on the magnet plate without disturbing the beads
- Added 200 μl of 80% EtOH to each tube while still the magnet not disturbing the beads
- Removed ALL the supernatant from each tube on the magnet plate without disturbing the beads. Extra EtOH blobs were removed with p20 pipette tips
- Resuspended beads in 16 μl 10 mM Tris HCl pH 8 and incubated tubes on shaker for 5 minutes
- Placed tubes back onto the magnet plate and removed supernatant when clear to new labeled PCR strip tubes

#### Qubit and TapeStation

Completed on Oct. 29, 2019

- Followed [Qubit protocol for BR DNA](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/Qubit-Protocol/)

|Sample|Avg ng/μl|
|----|----|
|Std 1|146 RFU|
|Std 2|15777 RFU|
|1.3|111|
|1.5|111.5|
|2.7|124|
|2.9|137.5|
|2.10|127|
|3.4|124|
|3.6|103|
|3.10|67.9|
|4.1|133|
|4.3|109|
|4.10|132|
|5.4|154|
|5.7|114.5|
|5.9|122.5|

- Followed [tapestation protocol for D5000 tapes](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/DNA-Tapestation/) on 3 representative samples to check

See full report [here](https://drive.google.com/a/uri.edu/file/d/1cCPnt_yHS88EhQcEintXUJ_LVdoQjqDH/view?usp=sharing)

![1](https://github.com/amyzyck/AmyZyck_Notebook/blob/master/images/Sample1.5.png)
![2](https://github.com/amyzyck/AmyZyck_Notebook/blob/master/images/Sample3.10.png)
![3](https://github.com/amyzyck/AmyZyck_Notebook/blob/master/images/Sample5.4.png)
