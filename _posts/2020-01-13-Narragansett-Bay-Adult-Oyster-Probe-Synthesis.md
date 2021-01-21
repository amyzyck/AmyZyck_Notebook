---
layout: post
title: Narragansett Bay Adult Oyster Probe Synthesis
date: '2020-01-13'
categories: Processing, Protocols
tags: [Narragansett Bay, Crassostrea virginica, Exome, Exome Capture, Probe Synthesiss, Expression, DNA, RNA]
projects: [Narragansett Bay]
---

### Probe Synthesis of mRNA Extracted from Larval Oysters

In 2017, [Puritz](https://github.com/jpuritz) and colleagues exposed larval oysters (_Crassostrea virginica_) to different coastal stressor treatments:
- Control
- Coastal Acidification
- Sewage Effluent
- Coastal Acidification + Sewage Effluent  

In 2017, [Puritz](https://github.com/jpuritz) and colleagues exposed larval oysters (_Crassostrea virginica_) to different coastal stressor treatments:
- Control
- Coastal Acidification
- Sewage Effluent
- Coastal Acidification + Sewage Effluent  

Larvae were periodically sampled for Expressed Exome Capture Sequencing ([EecSeq](https://github.com/jpuritz/EecSeq)).

[Maggie Schedl](https://meschedl.github.io/MES_Puritz_Lab_Notebook/) extracted mRNA from the larval oysters, performed mRNA capture and library prep, synthesized the mRNA into cDNA libraries, and pooled the cDNA libraries.

I picked up from here, using the cDNA libraries to generate enough sequence capture probes to capture exon regions of the adult oyster DNA samples.  

#### DSN Normalization
Completed on November 8, 2019.

First the pooled cDNA libraries were quantified following [Qubit protocol for BR DNA](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/Qubit-Protocol/)

|Sample|Avg ng/μl|
|----|----|
|Std 1|192 RFU|
|Std 2|20832 RFU|
|Sample|117|

***DSN Treatment***
- 500 ng of pooled cDNA libraries used
  - 500 ng/117 ng/ul = 4.3 ul of sample
    - add 9.2 ul of nuclease-free water to bring volume to 9.5 ul
- Make 4X hybridization buffer
  - 200 ul 1 M HEPES buffer solution
  - 400 ul 5 M NaCl solution
  - 400 ul nuclease-free water
- Add 4.5 ul of buffer to cDNA sample
- Put sample in Thermocycler using "DSN Program" for ~5 hours
- Pull Master Buffer, DSN enzyme, and Stop solution out of freezer to thaw
- Once thawed, dilute 10X DSN Master buffer to 2X
  - (10X)(x ul) = (2X)(20 ul)
    - Nuclease-free water = 16 ul
    - 10X Buffer = 4 ul
- Put diluted Master buffer in second thermocycler at 68 deg C hold for 10 minutes to come up to temperature
- Add 20 ul of Master buffer to cDNA sample in first thermocycler
  - pipette to mix -> set pipette to 33 ul
  - wait 10 minutes at 68 deg C
- Add 2 ul of DSN enzyme to sample in first thermocycler
  - Pipette to mix -> set pipette to 35 ul
  - wait 25 minutes at 68 deg C
- Add 40 ul DSN Stop Solution to tube and pipette to mix
  - immediately put the sample on ice then transfer to freezer
  - *Will bead clean and PCR amplify at a later date

***Post-DSN Cleanup and PCR***

Completed on November 11, 2019

__1.6X Beadclean__

- Made fresh 80% EtOH before starting
- Pulled KAPA Pure Beads out of fridge to warm to room temperature for ~30 minutes
- Added 128 ul of KAPA Pure Beads to sample and pipetted 10 times to mix
- Incubate at room temperature on shaker for 15 minutes
- Place tube on magnet, remove supernatant when clear
- Add 200 ul of 80% EtOH while sample is still on magnet
  - Remove clear supernatant
- Repeat previous step
  - Remove all of clear supernatant
- Resuspend the beads in 25 ul 10 mM Tris HCl and incubate for 5 minutes
- Put on magnet and transfer all 25 ul of the clear supernatant to a new labeled tube

__PCR__

- Use 20 ul of the DSN treated library
  - _the extra 5 ul are saved -> stored in the same container as the Adapter Working stocks_
- Add 25 ul of KAPA HiFi Hotstart Ready Mix to sample of DSN treated library
- Add 2.5 ul of diluted primers - Universal i5 and i7 library amp primers 20 uM - to sample
- Add 2.5 ul of nuclease-free water to sample
- Put sample in thermocycler using the "14 cycle DSN PCR" program

__1.6X Beaclean__

- Added 80 ul of KAPA Pure Beads to sample - pipette to mix
- Repeat the same bead clean steps from the section above
- Resuspend in 22 ul of 10 mM Tris HCl and incubate for 5 minutes
- Put on magnet, and transfer all 22 ul of the clear supernatant to a new labeled tube

__Qubit dsDNA Broad Range assay__

The DSN treated library was quantified following [Qubit protocol for BR DNA](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/Qubit-Protocol/)

- 199 ul x 3.2 samples = 636.8 ul of Buffer
- 1 ul x 3.2 samples = 3.2 ul of reagent

|Sample|Avg ng/μl|
|----|----|
|Std 1|194 RFU|
|Std 2|20560 RFU|
|Sample|8.61|

This is a low concentration, so I will do an additional 8 cycle PCR
  - Did 1.6X bead cleanup first
    - Added 32 ul of KAPA Pure Beads
    - Resuspended in 24 ul of 10 mM Tris HCl
      - _saved 4 ul_
- The 20 ul were split into 4 PCR tubes with 5 ul each
- PCR mastermix:
  - 52.5 ul KAPA ready mix
  - 5.25 ul of diluted primers
  - 26.46 ul of nuclease-free water
- Add 20 ul of mix to each tube
- Put samples in thermocycler using "8 cycle DSN PCR" program
- Take samples out of thermocycler and pool together - total of 100 ul
- Perform 1.6X Bead clean
  - Add 160 ul KAPA Pure beads
  - follow bead clean steps listed above
  - eluted in 60 ul 10 mM Tris HCl
    - _I accidentally eluted in 60 ul_

__Qubit dsDNA BR assay__

|Sample|Avg ng/μl|
|----|----|
|Std 1|184 RFU|
|Std 2|18286 RFU|
|Sample|86.8|

**_This concentration in 60 ul results in 5196 ng total of the DSN treated library. For the following probe synthesis step, I split the DSN treated library into 4 tubes each with 1 ug. I saved the extra 1 ug just in case._**

#### Restriction Digest of Adapters and MBN Treatment

Completed on November 12, 2019

- Make 4 PCR tubes with 11.55 ul of pooled DSN treated libraries (1 ug each)
- Bring the volume up to 12.25 ul with 0.7 ul of nuclease-free water
- Make Digest Master Mix:
  - 16.4 ul 10X Cutsmart buffer
  - 4.1 ul SAII enzyme  
  - 93.28 ul nuclease-free water
- Add 27.7 ul of mastermix to each sample on ice
- Put in thermocycler using " RE digest short" program for ~4 hours
- Make Mungbean mastermix:
  - 18.9 ul 10X Mungbean buffer
  - 2.1 ul Mungbean nuclease enzyme
- Add 5 ul of mastermix to each tube in thermocycler
- Run thermocycler program "MBN" for ~30 minutes

__1.5X Beadclean__

- Add 67.5 ul KAPA pure beads to each sample
- Perform bead clean steps listed above
- Elute in 22 ul 10 mM Tris HCl

**_I ran the samples on the TapeStation following [tapestation protocol for D5000 tapes](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/DNA-Tapestation/). The peaks for each sample were too high because I forgot to include the second adapter (NCO) during the digestion steps. I had to re-do the digestion._**

See full report [here](https://drive.google.com/file/d/14Aoi41bU_yXK8JgyF2hha6O_Prhjfqb8/view?usp=sharing)

Completed on November 15, 2019

Notes for re-do of digestion steps:
- Keep 21 ul (of the 22 ul) of DNA and adjust the volume of the nuclease-free water
- Use both SAII and NCO enzymes
- Also perform digest on 500 ng of saved DSN treated sample
  - 500 ng x 1 ul/86.6 ng = 5.77 ul -> add 15.23 ul nuclease-free water to get volume to 21 ul like the other samples
    - *saved the remaining 500 ng*

##### Re-do of digestion

- Make Digest Master Mix:
  - 4 ul of 10X Cutsmart Buffer x 5.1 samples = 20.4 ul
  - 1 ul of SAII - HF Enzyme x 5.1 samples = 5.1 ul
  - 1 ul of NCO Enzyme x 5.1 samples = 5.1 ul
  - 13 ul of nuclease-free waterx 5.1 samples = 66.3 ul
    - *this amount was adjusted from previously to account for the extra enzyme and extra DNA library volumes*
- Add 19ul of master mix to each sample with 21 ul of DSN treated libraries -> 40 ul total
- Put samples in thermocycler using "RE Digest short" program for ~4 hours
- Make Mungbean mastermix:
  - 4.5 ul of 10X Mungbean buffer x 5.2 samples = 23.4 ul
  - 0.5 ul of Mungbean nuclease enzyme x 5.2 samples = 2.6 ul
- Add 5 ul of mastermix to each sample
  - Pipette to mix and spin down
- Put samples in thermocycler using "MBN" program for ~30 minutes

__1.5X Beadclean__

- Add 67.5 ul of KAPA Pure Beads to each sample
- Follow beadclean steps listed above
- Elute in 21 ul 10 mM Tris HCl pH 8

__1.5X Beadclean__

- Add 31.5 ul of KAPA Pure beads
- Follow beadclean steps listed above
- Elute in 22 ul 10 mM Tris HCl pH 8

**_Ran these samples on the TapeStation and this time it worked!!_**

See full report [here](https://drive.google.com/file/d/1Ay_D_ttkG8uz0uoP3s7mea5rDXH-JuRc/view?usp=sharing)

#### Biotin Labeling

Completed on November 19, 2019

- Make Biotin mastermix:
  - 10 ul Decanucleotide in 5X reaction buffer x 5.2 samples = 52 ul
  - 14 ul Nuclease-free water x 5.2 samples = 72.8 ul
- In new PCR tubes, add 24 ul of mastermix to each tube
- Add 20 ul of DSN MBN libraries, pipette to mix and spin down
- Put in thermocycler using "Biotin-labing" program for ~10 minutes with a 4 deg hold
- Make Biotin-labeling mastermix:
  - 5 ul Biotin labeling mix x 5.2 samples = 26 ul
  - 1 ul Klenow fragment, exo(5u) x 5.2 samples = 5.2 ul
- Add 6 ul of mastermix to each tube, shake and spin down
- Continue "Biotin-labeling" program in thermocycler for ~20 hours

Continued on November 20, 2019

- Pooled all samples together - 250 ul total
- Performed 1.5X bead clean
  - Added 375 ul of KAPA Pure Beads
  - Completed bead clean steps listed above
  - Eluted in 52 ul of 10 mM Tris HCl pH 8

__Qubit dsDNA BR assay__

|Sample|Avg ng/μl|
|----|----|
|Std 1|185 RFU|
|Std 2|19212 RFU|
|Sample|53.2|

*__This is a low concentration of the probes, so I took the 5 ul of the DSN normalized libraries saved previously and ran a 22 cycle PCR__*

- Add 15 ul nuclease-free water to get 20 ul of the DSN Library
- Add 25 ul of KAPA HiFi Hotstart Ready mix
- Add 2.5 ul of diluted primers - Universal i5 i7 library amp primer 20 uM
- Add 2.5 ul of nuclease-free water
- Change the "DSN Treated PCR" thermocycler program to 22 cycles - runs ~1 hour

__1.6X Beadclean__

- Add 80 ul KAPA Pure Beads to sample
- Complete bead clean steps listed above
- Elute in 42 ul 10 mM Tris HCl pH 8

__Qubit dsDNA BR assay__

|Sample|Avg ng/μl|
|----|----|
|Std 1|198 RFU|
|Std 2|22112 RFU|
|Sample|67|

The DNA was over-amplified, so I used the DNA quantity of the non-over-amplified DNA - this info came from the TapeStation [see report here](https://drive.google.com/file/d/1tKlrKC8On5zEHnkmlSwUb8Ozg5mdSSIg/view?usp=sharing)
  - 44.9 ng/ul

To determine if I have enough DNA to complete the probe synthesis and have enough probes for the exome capture of my adult oyster DNA. The DSN libraries will be split into two tubes - one containing 1000 ng and the other containing 500 ng:  

1000 ng/44.9 ng/ul = 22.27 ul

500 ng/44.9 ng/ul = 11.14 ul

40 ul - 22.27 - 11.14 = 6.59 ul

44.9 ng/ul x 6.59 ul = 295.9 ng

*__Not enough DNA, so working with the extra 4 ul saved after the 14 cycle PCR__*

- Add 16 ul of Nuclease-free water to bring sample to 20 ul
- Add 25 ul HiFi Hotstart Readymix
- Add 2.5 ul of diluted primers - same as above
- Add 2.5 ul of Nuclease-free water  
- Put sample in thermocycler, changing "DSN Treated PCR" program to 8 cycles for 22 total cycles

__1.6X Beadclean__

- Add 80 ul KAPA Pure Beads
- Complete bead clean steps listed above
- Elute in 22 ul 10 mM Tris HCl pH 8

__Qubit dsDNA BR assay__

|Sample|Avg ng/μl|
|----|----|
|Std 1|201 RFU|
|Std 2|22277 RFU|
|Sample|92.8|

Again, the DNA was over-amplified, so I used the DNA quantity of the non-over-amplified DNA - this info came from the TapeStation [see report here](https://drive.google.com/file/d/1_bMSMn9mlHP9rP2_cAoYcGV26XbBucMH/view?usp=sharing)
  - 78.8 ng/ul

Again, the DSN libraries will be split into two tubes - one containing 1000 ng and the other containing 500 ng:

1000 ng/78.8 ng/ul = 12.69 ul

500 ng/78.8 ng/ul = 6.35 ul

20 ul - 12.69 - 6.35 = 0.96 ul

78.8 ng/ul x 0.96 ul = 75.65 ng

##### Digestion steps again

Completed November 22, 2019

Of the 4 samples, the largest volume was 22.27 ul, so the other 3 samples were brought up to that volume with nuclease-free water:

|Sample|DSN PCR library (ul)|Nuclease-free water (ul)|
|----|----|----|
|A|22.27|0|
|B|11.14|11.13|
|C|12.69|9.58|
|D|6.35|15.92|

- Make Digest Mastermix:
  - 4 ul 10X Cutsmart buffer x 4.1 samples = 16.4 ul
  - 1 ul SAII-HF Enzyme = 4.1 samples = 4.1 ul
  - 1 ul NCO Enzyme x 4.1 samples = 4.1 ul
  - 11.73 ul Nuclease-free water x 4.1 samples = 48.1 ul
- Add 17.73 ul of mastermix to each sample - 40 ul total
- Put samples in thermocycler using "RE Digest Short" program for ~4 hours
- Make Mungbean mastermix:
  - 4.5 ul of 10 X Mungbean buffer x 4.1 samples = 18.9 ul
  - 0.5 ul Mungbean nuclease x 4.2 samples = 2.1 ul
- Add 5 ul of mastermix to each sample - pipette to mix and spin down
- Put in thermocycler using "MBN" program for ~30 minutes

__1.5X Beadclean__

- Add 67.5 ul of KAPA Pure Beads to each sample
- Complete the bead clean steps listed above
- Elute in 21 ul 10 mM Tris HCl pH 8

__1.5X Beadclean__

- Add 31.5 ul of KAPA Pure Beads to each sample
- Complete the bead clean steps listed above
- Elute in 22 ul of 10 mM Tris HCl pH 8

##### Biotin labeling again

Completed on November 25, 2019

- Make Biotin mastermix:
  - 10 ul of Decanucleotide in 5X Reaction Buffer x 4.2 samples = 42 ul
  - 14 ul of nuclease-free water x 4.2 samples = 58.8 ul
- In new PCR tubes, add 24 ul of mastermix
- Add 20 ul of each sample (DSN-MBN treated libraries), one for each tube
  - pipette to mix
- Put in thermocycler using "Biotin-labeling" program for ~10 min until 4 deg hold
- Make Biotin-labeling mastermix:
  - 5 ul of Biotin-labeling mix x 4.2 samples = 21 ul
  - 1 ul Klenow fragment exo(5u) x 4.2 samples = 2.4 ul
- Add 6 ul of biotin labeling mix to each sample
  - Shake and spin down
- Continue "Biotin-labeling" program in thermocycler for ~20 hours

Next steps completed on November 26, 2019

- Pool all probes in 1 tube - 200 ul total

__1.5X Beadclean__

- Add 300 ul of KAPA Pure beads
- Complete bead clean steps listed above
- Elute in 42 ul of 10 mM Tris HCl pH 8

__Qubit dsDNA BR assay__

|Sample|Avg ng/μl|
|----|----|
|Std 1|199 RFU|
|Std 2|21973 RFU|
|Sample|73.8|

Sample was also run on the Tapestation - see report [here](https://drive.google.com/file/d/1m7I9DflECAqMyr9fBNsbdPKUSQuswS2c/view?usp=sharing).

73.8 ng/ul x 90 ul = 6642 ng

Again, this is not enough probes for what I need for the exome capture, so I'll go back to some of the extra DNA saved from an earlier step in the probe synthesis process.

Next steps completed on December 3, 2019

- Using the 500 ng of DNA saved from the DSN 14 + 8 PCR amplified libraries - take 250 ng and split into 5 tubes of  50 ng
  - 250 ng x 1 ul/86.6 ng = 2.89 ul
  - Add 2.89 ul 10 mM Tris HCl pH 8 to double
- In each tube add:
  - 25 ul KAPA HiFi Hotstart Readymix
  - 2.5 ul diluted primers - Universal i5 i7 library amp primers
  - 2.5 Nuclease-free water
- Put in thermocycler and run a 5 cycle PCR program
- Pool the 5 samples together - 250 ul total

__1.6X Beadclean__

- Add 400 ul of KAPA Pure Beads
- Complete the bead clean steps listed above
- Elute in 42 ul of 10 mM Tris HCl pH 8

__Qubit dsDNA BR assay__

|Sample|Avg ng/μl|
|----|----|
|Std 1|185 RFU|
|Std 2|21360 RFU|
|Sample|109|

Sample was also run on the Tapestation - see report [here](https://drive.google.com/file/d/116FAJDlSejTRavU_PJfww8Yn46GMnWEK/view?usp=sharing).

109 ng/ul x 40 ul = 4360 ng

1000 ng/109 ng/ul = 9.17 ul

##### Digestion steps again

Completed on December 4, 2019

- Make 4 PCR tubes with 9.17 ul of pooled-treated libraries (1 ug each)
- Bring up to 12.25 ul with 3.08 ul of nuclease-free water

*360 ng of extra pooled-treated libraries were saved in ~4 ul*

- Make Digest mastermix:
  - 4 ul of 10X Cutsmart buffer x 4.1 samples = 16.4 ul
  - 1 ul of SAII-HF Enzyme x 4.1 samples = 4.1 ul
  - 1 ul of NCO Enzyme x 4.1 samples = 4.1 ul
  - 21.75 ul of nuclease-free water x 4.1 samples = 89.18 ul
- Add 27.72 ul of mastermix to each tube - pipette to mix and spin down
- Put in thermocycler using "RE Digest short" program for ~4 hours
- Make Mungbean mastermix:
  - 4.5 ul of 10X Mungbean buffer x 4.2 samples = 18.9 ul
  - 0.5 ul of Mungbean nuclease x 4.2 samples = 2.1 ul
- Add 5 ul of Mungbean mastermix to each tube - pipette to mix and spin down
- Put samples in thermocycler using "MBN" program for ~30 minutes

__1.5X Beadclean__

- Add 67.5 ul KAPA Pure Beads to each tube
- Complete bead clean steps listed above
- Elute in 21 ul of 10 mM Tris HCl pH 8

__1.5X Beadclean__

- Add 31.5 ul KAPA Pure Beads to each tube
- Complete bead clean steps listed above
- Elute in 22 ul 10 mM Tris HCl pH 8

Samples were run on the Tapestation - see report [here](https://drive.google.com/file/d/1XDtXnjRuWBXfF2oqLqmPJqj9Q6ZFyMYW/view?usp=sharing).

##### Biotin labeling again

Completed December 5, 2019

- Make Biotin mastermix:
  - 10 ul of Decanucleotide in 5X Reaction buffer x 4.2 samples = 42 ul
  - 14 ul nuclease-free water x 4.2 samples = 58.8 ul
- In new PCR tubes, add 24 ul of mastermix to 4 tubes
- Add 20 ul of DSN-RE-MBN treated libraries in each tube
- Put in thermocycler using "Biotin" program for ~10 minutes until 4 deg hold
- Make Biotin-labeling mastermix:
  - 5 ul Biotin labeling mix x 4.2 samples = 21 ul
  - 1 ul Klenow fragment, exo(5u) x 4.2 samples = 4.2 ul
- Add 6 ul of biotin labeling mastermix to each of 4 tubes - shake and spin down
- Continue "Biotin" program for ~20 hours

Next steps completed on December 6, 2019

- Pool samples together - 200 ul total

__1.5X Beadclean__

- Add 300 ul of KAPA Pure Beads
- Complete bead clean steps listed above
- Elute in 52 ul of 10 mM Tris HCl pH 8

__Qubit dsDNA BR assay__

|Sample|Avg ng/μl|
|----|----|
|Std 1|194 RFU|
|Std 2|21524 RFU|
|Sample|68.8|

Sample was also run on the Tapestation - see report [here](https://drive.google.com/file/d/1TABZhtCSIpXIScEIgv8IhEzVlvR3024y/view?usp=sharing).

Determining if I have enough probes for exome capture:

68.8 ng/ul x 140 ul = 9632 ng

500 ng x 1 ul/68.8 ng = 7.27 ul per capture across 5 captures
