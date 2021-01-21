---
layout: post
title: Narragansett Bay Adult Oyster Hybridization and Capture
date: '2021-01-21'
categories: Processing, Protocols
tags: [Narragansett Bay, Crassostrea virginica, Exome, Exome Capture, Hybridization, DNA, RNA]
projects: [Narragansett Bay]
---

### Hybridization of sequence capture probes and adult oyster DNA

Steps for completing the library preparation of adult oyster DNA can be accessed here:
  - [Part 1](https://amyzyck.github.io/AmyZyck_Notebook/Narragansett-Bay-Adult-Oyster-DNA-Library-Prep/)
  - [Part 2](https://amyzyck.github.io/AmyZyck_Notebook/Narragansett-Bay-Adult-Oyster-DNA-Library-Prep-Part-2/)
  - [Part 3](https://amyzyck.github.io/AmyZyck_Notebook/Narragansett-Bay-Adult-Oyster-DNA-Library-Prep-Part-3/)
  - [Part 4](https://amyzyck.github.io/AmyZyck_Notebook/Narragansett-Bay-Adult-Oyster-DNA-Library-Prep-Part-4/)

Steps for completing the probe synthesis can be accessed [here](https://amyzyck.github.io/AmyZyck_Notebook/Narragansett-Bay-Adult-Oyster-Probe-Synthesis/)

#### Pool Adult DNA library samples into 5 capture pools

Completed on December 10, 2019

Samples were assigned to a specific capture pool prior to DNA library prep. Each sample in a capture pool has a unique index primer pair and adapter combo. This will allow us to differentiate the samples following sequencing.
- Pool 200 ng of each DNA library

__Capture 1__

|Sample|Vol. of DNA for 200 ng (ul)|
|----|----|
|1.1|1.74|
|1.6|1.89|
|2.1|1.67|
|2.6|2.06|
|3.1|1.80|
|3.6|1.96|
|4.1|1.52|
|4.6|2.44|
|5.1|1.77|
|5.6|4.29|
|Total|21.14|

__Capture 2__

|Sample|Vol. of DNA for 200 ng (ul)|
|----|----|
|1.2|2.94|
|1.7|1.71|
|2.2|1.34|
|2.7|1.61|
|3.2|1.54|
|3.7|2.21|
|4.2|1.27|
|4.7|2.00|
|5.2|1.37|
|5.7|1.77|
|Total|17.76|

__Capture 3__

|Sample|Vol. of DNA for 200 ng (ul)|
|----|----|
|1.3|1.83|
|1.8|1.32|
|2.3|1.96|
|2.8|2.43|
|3.3|2.29|
|3.8|2.03|
|4.3|1.85|
|4.8|1.69|
|5.3|1.27|
|5.8|3.04|
|Total|19.71|

__Capture 4__

|Sample|Vol. of DNA for 200 ng (ul)|
|----|----|
|1.4|1.71|
|1.9|1.53|
|2.4|1.77|
|2.9|1.47|
|3.4|1.64|
|3.9|2.00|
|4.4|2.20|
|4.9|1.38|
|5.4|1.31|
|5.9|1.64|
|Total|16.65|

__Capture 5__

|Sample|Vol. of DNA for 200 ng (ul)|
|----|----|
|1.5|1.82|
|1.10|1.53|
|2.5|1.40|
|2.10|1.59|
|3.5|1.60|
|3.10|2.98|
|4.5|1.64|
|4.10|1.53|
|5.5|1.36|
|5.10|1.54|
|Total|16.99|

#### Hybridization

Completed on December 10, 2019

- Add 500 ng of probes to each pooled capture
  - 500 ng/68.8 ng/ul = 7.27 ul
- Add nuclease-free water to bring volume up to 29.37
|Sample|Vol. pooled w/ probes (ul)|Vol. of water (ul)|
|----|----|----|
|Capture 1|28.41|0.96|
|Capture 2|25.03|4.34|
|Capture 3|26.98|2.39|
|Capture 4|23.92|5.45|
|Capture 5|24.26|5.11|

- Make Hybridization mastermix:
  - 15 ul of SSC (20X) x 5.3 samples = 79.5 ul
  - 0.5 ul of EDTA (500 mM) x 5.3 samples = 2.65 ul
  - 0.5 ul of SDS (10%) x 5.3 samples = 2.65 ul
  - 2.00 ul of Denhardt's solution x 5.3 samples = 10.6 ul
  - 0.63 ul Cot-1 DNA (1 mg/ml) x 5.3 samples = 3.34 ul
  - 0.5 ul of Blocking oligo 1 (200 uM) x 5.3 samples = 2.65 ul
  - 0.5 ul of Blocking oligo 2 (200 uM) x 5.3 samples = 2.65 ul
  - 0.5 ul of Blocking oligo 3 (200 uM) x 5.3 samples = 2.65 ul
  - 0.5 ul of Blocking oligo 4 (200 uM) x 5.3 samples = 2.65 ul
- Add 20.63 ul of mastermix to each tube and pipette to mix
- Put samples in thermocycler using "Hybridization" program for 10 minutes
- Put tube rack with samples in plastic bag with damp paper towel and transfer to already warmed incubator genie
  - Set at 65 deg C rocking at 10 speed for 48 hours
  - Vortex and spin down samples after 24 hours and replace the paper towel with a fresh damp one

#### Wash and Capture

Completed on December 12, 2019

Creating various wash solutions for washes of the hybridized probes and adult DNA libraries

- Create TEN solution - need 5,500 ul
  - 0.5 ul of 500 mM EDTA x 5.5 samples = 2.75 ul x 4 uses = 11 ul
  - 50 ul 5 M NaCl x 5.5 samples = 275 ul x 4 uses = 1100 ul
  - 199.5 ul 10 mM Tris HCl pH 7.5 x 5.5 samples = 1097.25 ul x 4 uses = 4389 ul
- Solution 1 (1X SSC, 0.1% SDS) - need 2,200 ul
  - 10 ul of 20X SSC x 5.5 samples = 55 ul x 2 uses = 110 ul
  - 2 ul of 10% SDS x 5.5 samples = 11 ul x 2 uses = 22 ul
  - 188 ul of nuclease-free water x 5.5 samples = 1034 ul x 2 uses = 2068 ul
  - *warmed to 65 deg C in thermomixer, put in 2 1.5 ml tubes with 1,100 ul in each*
- Solution 2 (0.5X SSC, 0.1% SDS) - need 1,100 ul
  - 5 ul of 20X SSC x 5.5 samples = 27.5 ul
  - 2 ul of 10% SDS x 5.5 samples = 11 ul
  - 193 ul of nuclease-free water x 5.5 samples = 1061.5 ul
- Solution 3 (0.1X SSC, 0.1% SDS) - need 1,100 ul
  - 1 ul of 20X SSC x 5.5 samples = 5.5 ul
  - 2 ul of 10% SDS x 5.5 samples = 11 ul
  - 197 ul of nuclease-free water x 5.5 samples = 1083.5 ul

**__Prepare Dynabeads__**  
- Resuspend Dynabeads M-280 beads first with p200
- Make 5 1.5-ml tubes with 10 ul of resuspended beads in each
- Add 250 ul of prepared TEN solution to each tube - pipette to mix
- Place tubes on magnet and remove supernatant when clear
- Remove the tubes from the magnet and resuspend beads in 250 ul of TEN solution
- Repeat the previous three wash steps two more times for 3 washes total
- Resuspend the beads in 250 ul of TEN solution  

**__Capture__**
- After the 48 hour hybridization incubation, take the hybridized pools out of the incubator and spin down
- Add 50 ul of each of the 5 hybridization mixtures to each of 5 washed and prepared Dynabead PCR tubes (separate tube for each hybridization mixture)
- Pipette to mix and incubate on shaker at room temperature for 30 minutes
- Place Solution 1 in thermomixer to heat up to 65 deg C
- *Make PCR strip tubes to save every wash - 25 total tubes*
- After 30 minute incubation, place tubes on magnet
- Remove supernatant when clear and save in "Start" tube
- Resuspend beads in 200 ul of the 65 deg C heated Solution 1
- Place tubes in thermomixer set at 65 deg C for 15 minutes
- After 15 minute incubation, place tubes on magnet - *beads had fallen to the bottom of the tube during the incubation*
- Remove supernatant when clear and save in "Wash 1" tube
- Resuspend beads in 200 ul of the 65 deg C heated Solution 1
- Place tubes in thermomixer set at 65 deg C for 10 minutes
- After the 10 minute incubation, place tubes on magnet
- Remove supernatant when clear and save in "Wash 2" tube
- Resuspend beads in 200 ul of room temp Solution 2
- Place tubes in thermomixer set at 65 deg C for 10 minutes
- After the 10 minute incubation, place tubes on magnet
- Remove supernatant when clear and save in "Wash 3" tube
- Resuspend beads in 200 ul of room temp Solution 3
- Place tubes in thermomixer set at 65 deg C for 10 minutes
- Turn on thermomixer and turn on "80 deg C hold" program
- Place 200 ul of nuclease-free water in 80 deg C thermomixer
- After 10 minute incubation, place tubes on magnet
- Remove supernatant when clear and save in "Wash 4" tube
- Resuspend beads in 22 ul of 80 deg C heated nuclease-free water
- Place tubes in thermomixer set at 80 deg C for 10 minutes

**__PCR amplification__**
- Make PCR mastermix for amplification:
  - 12.5 ul of KAPA HiFi Hotstart Readymix x 5.2 samples = 65 ul
  - 2.5 ul of KAPA universal primer mix x 5.2 samples = 13 ul
- Aliquot 15 ul of PCR mastermix to each of 5 new PCR tubes labeled for each capture
- After the 10 minute incubation, spin down the Dynabead tubes and place  on magnet
- Save supernatant when clear as captured DNA into new strip tubes
  - *more than 22 ul in each tube, possibly leftover from the other washes?*
  - the beads were resuspended in 20 ul of nuclease-free water and incubated for 10 minutes then saved (clear supernatant removed from beads) just to be safe
- Transfer 10 ul of the captured DNA to corresponding PCR amp tubes - vortex and spin down
- Place tubes in thermocycler for "post-capture 12-cycle PCR" program
- *Place the other tubes (all saved washes and remaining 10 ul of captured DNA) in -20 deg C freezer
  - Saved in box labeled EecSeq Samples etc.

__1X Beadclean__

- After PCR, perform 1X beadclean
- Made fresh 80% EtOH before starting
- Pulled KAPA Pure Beads out of fridge to warm to room temperature for ~30 minutes
- Added 25 ul of KAPA Pure Beads to sample and pipetted 10 times to mix
- Incubate at room temperature on shaker for 15 minutes
- Place tube on magnet, remove supernatant when clear
- Add 200 ul of 80% EtOH while sample is still on magnet
  - Remove clear supernatant
- Repeat previous step
  - Remove all of clear supernatant
- Resuspend the beads in 25 ul 10 mM Tris HCl pH 8 and incubate for 5 minutes
- Put on magnet and transfer all 25 ul of the clear supernatant to a new labeled tube

__Qubit dsDNA High Sensitivity assay__

The captured pools were quantified following [Qubit protocol for BR DNA](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/Qubit-Protocol/)

- 199 ul x 7.5 samples = 1492.5 ul of Buffer
- 1 ul x 7.5 samples = 7.5 ul of reagent

|Sample|Avg ng/μl|
|----|----|
|Std 1|46 RFU|
|Std 2|23673 RFU|
|Capture1|18.3|
|Capture2|18.6|
|Capture3|25|
|Capture4|18.1|
|Capture5|30.2|

Captures were also run on the TapeStation following [tapestation protocol for D5000 tapes](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/DNA-Tapestation/).

See full report [here](https://drive.google.com/file/d/1WFKPPqsB0pHbEAF3zsWB1h-MQGmL9vX9/view?usp=sharing).

These pools are ready to be sent off for sequencing!!

### Sending samples off for sequencing

Completed on December 18, 2019

- Label tubes both caps and sides
  - NBAOcapture1
  - NBAOcapture2
  - NBAOcapture3
  - NBAOcapture4
  - NBAOcapture5
- Transfer 15 ul of the captured DNA pools to each of the labeled tubes
