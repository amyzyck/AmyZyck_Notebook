---
layout: post
title: Narragansett Bay Adult Oyster DNA Preparation for Sonication - Part 2
date: '2021-04-29'
categories: Processing, Protocols
tags: [Narragansett Bay, Crassostrea virginica, oyster, Bead clean, DNA]
projects: [Narragansett Bay]
---

### 1X Bead clean to concentrate DNA into smaller volume before sonication

Completed April 19, 2021

Before sonicating the DNA, a few samples need to have the DNA concentrated into a smaller volume. This is necessary because some samples had too little DNA to achieve 500 ng of DNA in 51 ul (volume needed for sonication).

|Sample|Description|Volume for 500 ng (ul)|Volume of Beads (ul)|
|----|----|----|----|
|GHP_2|Third extraction E2|60|60|
|MCD_10|Third extraction E2 gill tissue|150|150|

- _Made fresh 80% EtOH_
- _Took KAPA Pure Beads out of fridge beforehand to warm to room temp for about 30 minutes_
- Vortex and spin down DNA samples
- For sample MCD_10, add 3.2G sample volume (all) to M & G E2 combined sample (made previously), for a total volume of 294 uL
- In new 1.5 mL tubes, add appropriate volume of sample (see column 3 in table above)
- Add appropriate volume of KAPA Pure Beads (see column 4 in table above) to each sample and pipette up and down 10 times to mix (_avoid bubbles_)
- Place tubes on shaker at room temp for 15 minutes - shaker set to 200 rpm's
- After 15 minute incubation, place tubes on magnet plate and remove supernatant from tubes when it was fully clear not disturbing the beads
  - Dispose of liquid in liquid waste beaker
- Add 200 μl of 80% EtOH to each tube while still the magnet not disturbing the beads
- Remove supernatant from each tube on the magnet plate without disturbing the beads
- Add 200 μl of 80% EtOH to each tube while still the magnet not disturbing the beads
- Remove ALL the supernatant from each tube on the magnet plate without disturbing the beads. Extra EtOH blobs were removed with p20 pipette tips
- Resuspend beads in 20 μl of 10 mM Tris HCl pH 8 for sample GHP_2 and 51 uL for sample MCD_10
- Incubate tubes at room temp on shaker for 5 minute
- Place tubes on magnet plate and transfer supernatant when clear to new labeled 1.5 mL tubes

*Some samples needed a little more DNA to reach 500 ng, so I took DNA from other extractions/elutions (within the same sample) to reach concentration*

|Sample|Sample Type 1 Description|Sample Type 2 Description|Type 2 Volume to add for 500 ng (ul)|Total Volume after 1 uL taken for Qubit (ul)|
|----|----|----|----|----|
|NAR_3|Reconcentrated DNA in 30 uL|Extraction 1 E2|12|41|
|NAR_5|Reconcentrated DNA in 30 uL|Extraction 2 E1|2.5|31.5|
|NAR_6|Reconcentrated DNA in 30 uL|Extraction 1 E1|2.7|31.7|
|NAR_7|Reconcentrated DNA in 30 uL|Extraction 2 E1|3|32|
|GHP_1|Reconcentrated DNA in 30 uL|Extraction 1 E1|3.75|32.75|
|GHP_2|Reconcentrated DNA in 30 uL|Extraction 3 E2|20|49|
|GHP_3|Reconcentrated DNA in 30 uL|Extraction 1 E2|21|50|

- Added volume of Type 2 (column 4) to Type 1 tube (column 2)
  - Vortex and spin down

#### Qubit dsDNA BR assay

- Followed [Qubit protocol for BR DNA](https://meschedl.github.io/MESPutnam_Open_Lab_Notebook/Qubit-Protocol/)

|Sample|Avg ng/μl|
|----|----|
|Std 1|170 RFU|
|Std 2|20487 RFU|
|NAR_3|12.7|
|NAR_5|20.0|
|NAR_6|20.6|
|NAR_7|21.6|
|GHP_1|16.3|
|GHP_2|7.78|
|GHP_3|6.82|
|MCD_10|Too Low|

Confirming that I have enough DNA in these samples:

|Sample|Qubit concentration (ng/uL)|Vol. of Tris (uL)|Total DNA (ng)|
|----|----|----|----|
|NAR_3|12.7|41|520.7|
|NAR_5|20.0|31.5|630|
|NAR_6|20.6|31.7|653.02|
|NAR_7|21.6|32|691.2|
|GHP_1|16.3|32.75|533.83|
|GHP_2|7.78|49|381.22|
|GHP_3|6.82|50|341|
|MCD_10|Too Low|46|Too Low|

GHP_2 and GHP_3 are too low, so adding more DNA:

|Sample|Type to add|Qubit conc. (ng/uL)|Vol. of sample to add (uL)|Total volume (uL)|
|----|----|----|----|----|
|GHP_2|Extraction 3 E1|144|2|51|
|GHP_3|Extraction 1 E1|180|1|51|

The MCD_10 sample DNA concentration is too low, so I will proceed using DNA from Extraction 2 E1 for this sample. Ready to move on to sonication.
