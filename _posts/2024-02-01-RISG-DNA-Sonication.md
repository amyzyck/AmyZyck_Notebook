---
layout: post
title: RISG DNA Sonication
date: '2024-02-01'
categories: Processing, Protocols
tags: [Crassostrea virginica, oyster, DNA, Sonication, Bead Clean]
projects: [Rhode Island Sea Grant]
---

## Sonication of oyster DNA samples for shearing to 300 bp

DNA extractions were previously performed on both [adult](https://amyzyck.github.io/AmyZyck_Notebook/RISG-Zymo-DNA-Extractions-of-Adult-Oyster-Samples/) and [larval](https://amyzyck.github.io/AmyZyck_Notebook/RISG-Zymo-DNA-RNA-Extractions-of-Larval-Oyster-Samples/) oyster samples. 

This is the general protocol I followed for DNA Sonication. I typically processed 16 samples at a time and could complete multiple sonication runs in a day. 

### Sonication
- Samples were sonicated following the [QSonica Protocol](https://github.com/meschedl/PPP-Lab-Resources/blob/master/Protocols_and_Lab_Resources/General_Equptment_Protocols/Sonicator/QSonica-General-Protocol.md)
- Prep samples in QSonica tubes 
    - Aliquot 500 ng of DNA sample into tube (calculated based on Qubit concentrations after DNA extractions)
    - Add 10 mM Tris HCl pH 8.0 to achieve a total volume of 100 μL
- Vortex and spin down 
- Sonicate samples for 5 minutes
    - Pulse setting at 15 seconds on and 15 seconds off
    - Amplitude = 35%  
    - Pause program and spin down tubes every 2 minutes 

### 1.8X Bead Clean
After sonicating, perform 1.8X bead clean with [KAPA Pure Beads](https://sequencing.roche.com/us/en/products/group/kapa-pure-beads.html#documents) 

- Make 80% Ethanol (make fresh daily)
    - For a total batch of 20 mL, add 16 mL of 200 proof EtOH and 4 mL Type II DI Water 
- Take KAPA Pure Beads out of 4 degrees C fridge and keep in drawer (light sensitive) to warm to room temperature for 30 minutes 
- Add 180 μL of KAPA Pure Beads to each sample and pipette to mix 
- Incubate at room temperature on shaker for 15 minutes
- Place tubes on magnet and remove and discard supernatant (~277 μL) when clear 
- Add 200 μL of 80% EtOH to each tube while still on magnet - don't disturb beads collected on magnet
- Remove and discard 197 μL of clear supernatant
- Add 190 μL of 80% EtOH to each tube while still on magnet - don't disturb beads
- Remove and discard *all* (200 μL) clear supernatant 
- Remove any droplets collected on sides of tube with a p20 pipette tip 
- **Don't let beads sit dry for more than 2 minutes, this can result in large losses of DNA**
- Take tubes off of magnet, and resuspend the beads in 30 μL room temperature 10 mM Tris HCl pH 8.0
- Incubate on shaker for 5 minutes
- Make a set of final PCR strip tubes 
- Place samples on magnet, transfer clear supernatant to final PCR strip tubes 

#### Quality Control Check 

**Qubit**
- Concentrations for a subset of sonicated DNA samples are checked using the Biotium [dsDNA Broad Range](https://biotium.com/wp-content/uploads/2017/12/PI-31069.pdf) quantitation kit

**TapeStation**
- Shearing accuracy is checked for a subset of samples using the [D1000 ScreenTape Assay](https://www.agilent.com/cs/library/usermanuals/public/ScreenTape_D1000_QG.pdf)
- Sample TapeStation report can be accessed [here](https://drive.google.com/file/d/1XI0EvmgOH2H9qn_Most-JVfuv8MoUGWY/view?usp=sharing)