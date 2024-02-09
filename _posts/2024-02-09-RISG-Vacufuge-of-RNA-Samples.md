---
layout: post
title: RISG Vacufuge of RNA Samples
date: '2024-02-09'
categories: Processing, Protocols
tags: [Crassostrea virginica, oyster, RNA, Concentration]
projects: [Rhode Island Sea Grant]
---

## Concentrating RNA samples using Vacufuge

For the RISG project, we decided to pool the three replicate RNA samples for each treatment before moving forward with mRNA Sequencing Library Prep. For mRNA Seq Prep, the desired starting input was 1200 ng of RNA concentrated in 25 μL. 

For 10 pooled sample sets, the pooled volume to achieve 1200 ng of RNA was greater than 25 μL. A vacufuge was used to concentrate these samples down into 25 μL. 

### Vacufuge sample preparation 
- Before pooling samples, make new 1.5 mL tubes 
    - *I added 25 μL of nuclease-free water into each tube, marked the outside of the tube at the water line with a Sharpie, and then pipetted out the water*
    - *This was used as a visual guide when vacufuging the samples*
- For each of the 3 RNA samples going into the pool, aliquot 500 ng of RNA 
    - *I decided to vacufuge 1500 ng of RNA, in case there was any loss of RNA during the vacufuge process* 
- Place tubes in vacfuge and use the following settings:
    - Brake: ON
    - Temp: Ambient (--)
    - Mode: V-AQ
    - Time: (this will depend on the starting volume in the samples)
        - *I started with 15 minutes and recorded the final time it took to vacufuge samples to 25 μL*

|     Sample    | Aliqout for 1500 ng (μL) | Vacufuge time (minutes) |  
|---------------|--------------------------|-------------------------|
|  B2_TSE1_Con  |         60.37            |            40           |
| B2_TSE1_ConSE |         48.30            |            30           |
|  B2_TSE1_Hi   |         80.28            |            50           |
| B2_TSE1_HiSE  |         64.70            |            40           |
|   B3_TSE1_Hi  |         35.07            |            15           |
| B3_TSE1_HiSE  |         34.13            |            15           |
|   B4_TCE_HB   |         44.98            |            30           |
|  B4_TSE1_Con  |         36.59            |            15           |
|  B4_TSE1_Hi   |         31.69            |            15           |
| B4_TSE1_HiSE  |         39.98            |            30           |

**RNA BR Assay Qubit**

|     Sample    | Qubit 1 (ng/μL) | Qubit 2 (ng/μL) |
|---------------|-----------------|-----------------|
|     Std. 1    |      76.39      |                 |
|     Std. 2    |     5547.23     |                 |
|  B2_TSE1_Con  |       59.8      |       60.2      |
| B2_TSE1_ConSE |       61.2      |       61.2      |
|  B2_TSE1_Hi   |       58.0      |       58.0      |
| B2_TSE1_HiSE  |       55.4      |       56.0      |
|   B3_TSE1_Hi  |       59.4      |       60.2      |
| B3_TSE1_HiSE  |       61.6      |       62.2      |
|   B4_TCE_HB   |       83.2      |       83.0      |
|  B4_TSE1_Con  |       58.8      |       56.8      |
|  B4_TSE1_Hi   |       67.4      |       67.4      |
| B4_TSE1_HiSE  |       88.8      |       89.2      |

*I seemed to have over-vacufuged 4 of the pooled samples, I don't have enough volume to achieve 1200 ng.*
- Samples:
    - B2_TSE1_Con
    - B2_TSE1_Hi
    - B2_TSE1_HiSE
    - B4_TSE1_HiSE

I re-did these four samples:

|     Sample    | Vacufuge time (minutes) |  
|---------------|-------------------------|
|  B2_TSE1_Con  |           30            |
|  B2_TSE1_Hi   |           36            |
| B2_TSE1_HiSE  |           33            |
| B4_TSE1_HiSE  |           20            |

**RNA BR Assay Qubit**

|     Sample    | Qubit 1 (ng/μL) | Qubit 2 (ng/μL) |
|---------------|-----------------|-----------------|
|     Std. 1    |      75.49      |                 |
|     Std. 2    |     5606.77     |                 |
|  B2_TSE1_Con  |      55.4       |     55.8        |
|  B2_TSE1_Hi   |      45.0       |     45.0        |
| B2_TSE1_HiSE  |      65.8       |     65.8        |
| B4_TSE1_HiSE  |      72.6       |     73.0        |  



Again, I did not have enough volume to achieve 1200 ng. I decided to take 600 ng from each vacufuge round and combine them.

|     Sample    | Aliquot for 600 ng (Vacufuge round 1) | Aliquot for 600 ng (Vacufuge round 1) | Final Volume |
|---------------|---------------------------------------|---------------------------------------|-------|
|  B2_TSE1_Con  |            10.03 μL                   |               10.83 μL                |  20.86 μL  |
|  B2_TSE1_Hi   |            10.34 μL                   |               13.33 μL                |  23.68 μL  |
| B2_TSE1_HiSE  |            10.83 μL                   |               9.12 μL                 |  19.95 μL  |
| B4_TSE1_HiSE  |            6.76 μL                    |               8.26                    |  15.02 μL  |

These 10 samples are ready to go for mRNA Seq Library Prep. 
