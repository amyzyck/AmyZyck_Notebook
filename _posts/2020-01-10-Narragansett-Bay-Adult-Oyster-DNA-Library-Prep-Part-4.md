---
layout: post
title: Narragansett Bay Adult Oyster DNA Library Prep Part 4
date: '2020-01-10'
categories: Processing, Protocols
tags: [Narragansett Bay, Crassostrea virginica, DNA, Library Prep]
projects: [Narragansett Bay]
---

### DNA Library Prep for NB Adult Oyster EecSeq - 14 Samples

***Initial bead cleanup was performed on Oct. 25, 2019 and library prep was performed on Nov. 2, 2019.***

Using the [KAPA HyperPrep DNA Library Prep Kit](https://sequencing.roche.com/en-us/products-solutions/by-category/library-preparation/dna-library-preparation/kapa-hyperprep.html) on 14 DNA samples in 10 mM Tris HCl pH 8 containing 500 ng from the first 50 samples of the NB adult oyster experiment.

Previously, all samples were sonicated to 150 bp following the [QSonica protocol](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/Qsonica/)- instructions can be found [here](https://amyzyck.github.io/AmyZyck_Notebook/Narragansett-Bay-Adult-Oyster-DNA-Sonication-Part-2/).

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
  - ERAT buffer: 3.5 μl * 15 = 52.5 μl
  - ERAT enzyme: 1.5 μl * 15 = 22.5 μl
- In the 14 PCR strip tubes containing the 25 μl of 500 ng sheared DNA, added 5 μl of ERAT master mix
- Vortexed and spun down
- Placed samples in thermocycler A-tailing program in JONP login - program runs for ~ 1 hour

#### Adapter Ligation

***Working adapter stocks 1-7, and 9-12 were diluted on Oct. 10, 2019; working adapter stock 8 was diluted on Oct. 21, 2019.*** Dilution was completed as followed:

- In new PCR strip tubes, added 20 μl of previously made annealed adapter stocks
- Added 20 μl of Nuclease free water to annealed adapter stocks for ***40 μl total of 20 μM adapter stocks***


- Prepared adapter ligation master mix:
  - Ligation buffer: 15 μl * 15.5 = 232.5 μl
  - DNA ligase: 5 μl * 15.5 = 77.5 μl
  - Nuclease free water: 2.5 μl * 15.5 = 38.75 μl
- Added 22.5 μl of ligation master mix and appropriately planned adapters to each sample. _Adapters were added last to minimize adapter-adapter ligation_.

|Sample|LMM|Adapter|
|---|---|---|
|1.4|22.5μl|2.5μl 4|
|1.7|22.5μl|2.5μl 7|
|1.9|22.5μl|2.5μl 9|
|2.1|22.5μl|2.5μl 11|
|2.3|22.5μl|2.5μl 1|
|2.4|22.5μl|2.5μl 2|
|3.1|22.5μl|2.5μl 9|
|3.3|22.5μl|2.5μl 11|
|3.7|22.5μl|2.5μl 3|
|4.6|22.5μl|2.5μl 12|
|4.8|22.5μl|2.5μl 2|
|5.1|22.5μl|2.5μl 5|
|5.3|22.5μl|2.5μl 7|
|5.10|22.5μl|2.5μl 2|

- Pipetted up and down with multichannel to mix - pipette set to 50 μl
  - spin down
- Incubated samples on shaker at room temp for 1 hour

#### 0.8X Cleanup

- _Made fresh 80% EtOH_
- _Took KAPA Pure Beads out of fridge beforehand to warm to room temp_
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
- Amp MM A - Sample 1.4
  - 12.5 μl HotStart Ready mix
  - 1.25 μl 501 primer
  - 1.25 μl 701 primer
- Amp MM B - Samples 1.7 & 1.9
  - 12.5 μl HotStart Ready mix * 2.2 = 27.5 μl
  - 1.25 μl 502 primer * 2.2 = 2.75 μl
  - 1.25 μl 702 primer * 2.2 = 2.75 μl
- Amp MM C - Samples 2.1, 2.3, & 2.4
  - 12.5 μl HotStart Ready mix * 3.2 = 40 μl
  - 1.25 μl 503 primer * 3.2 = 4 μl
  - 1.25 μl 703 primer * 3.2 = 4 μl
- Amp MM D - Samples 3.1 & 3.3
  - 12.5 μl HotStart Ready mix * 2.2 = 27.5 μl
  - 1.25 μl 505 primer * 2.2 = 2.75 μl
  - 1.25 μl 705 primer * 2.2 = 2.75 μl
- Amp MM E - Sample 3.7
  - 12.5 μl HotStart Ready mix
  - 1.25 μl 506 primer
  - 1.25 μl 706 primer
- Amp MM F - Samples 4.6 & 4.8
  - 12.5 μl HotStart Ready mix * 2.2 = 27.5 μl
  - 1.25 μl 508 primer * 2.2 = 2.75 μl
  - 1.25 μl 708 primer * 2.2 = 2.75 μl
- Amp MM G - Samples 5.1 & 5.3
  - 12.5 μl HotStart Ready mix * 2.2 = 27.5 μl
  - 1.25 μl 509 primer * 2.2 = 2.75 μl
  - 1.25 μl 709 primer * 2.2 = 2.75 μl
- Amp MM H - Sample 5.10
  - 12.5 μl HotStart Ready mix
  - 1.25 μl 510 primer
  - 1.25 μl 710 primer
- Prepared new PCR tubes for the amplification with the following:

|Sample|volume adapter added DNA of sample|volume of Amp MM|
|---|----|----|
|1.4|10μl|15μl Amp MM A|
|1.7|10μl|15μl Amp MM B|
|1.9|10μl|15μl Amp MM B|
|2.1|10μl|15μl Amp MM C|
|2.3|10μl|15μl Amp MM C|
|2.4|10μl|15μl Amp MM C|
|3.1|10μl|15μl Amp MM D|
|3.3|10μl|15μl Amp MM D|
|3.7|10μl|15μl Amp MM E|
|4.6|10μl|15μl Amp MM F|
|4.8|10μl|15μl Amp MM F|
|5.1|10μl|15μl Amp MM G|
|5.3|10μl|15μl Amp MM G|
|5.10|10μl|15μl Amp MM H|

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

Completed on Nov. 3, 2019

- Followed [Qubit protocol for BR DNA](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/Qubit-Protocol/)

|Sample|Avg ng/μl|
|----|----|
|Std 1|180 RFU|
|Std 2|20009 RFU|
|1.4|117|
|1.7|117.5|
|1.9|131|
|2.1|120|
|2.3|102.5|
|2.4|116|
|3.1|111|
|3.3|88.0|
|3.7|90.5|
|4.6|82.8|
|4.8|120|
|5.1|114|
|5.3|158.5|
|5.10|131.5|

- Followed [tapestation protocol for D5000 tapes](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/DNA-Tapestation/) on 5 representative samples to check

See full report [here](https://drive.google.com/a/uri.edu/file/d/1uo-bRi6GEm8IEmvUvDekvaTd5QmvbmBp/view?usp=sharing)

Sample 1.7:
![Sample1.7]({{ site.baseurl}}/images/Sample1.7.png "Sample1.7")

Sample 3.3:
![Sample3.3]({{ site.baseurl}}/images/Sample3.3.png "Sample3.3")

Sample 3.7:
![Sample3.7]({{ site.baseurl}}/images/Sample3.7.png "Sample3.7")

Sample 4.6:
![Sample4.6]({{ site.baseurl}}/images/Sample4.6.png "Sample4.6")

Sample 5.3:
![Sample5.3]({{ site.baseurl}}/images/Sample5.3.png "Sample5.3")
