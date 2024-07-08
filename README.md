# HARDAT: Human-Action-Recognition Dataset for Manual Assembly Tasks
This page is under construction and will be completed with the publication of the paper.

## Introduction
This repository holds supplementary information and statistics on the HARDAT paper as well as instructions for downloading the dataset.

## Related Publication and Citation
This repository serves as a complement for the following [paper](). Please cite this  work if you use the HARDAT dataset in your research.

```
@article{Buesch.,
title = {HARDAT: Human-Action-Recognition Dataset for Manual Assembly Tasks},
journal = {},
volume = {},
pages = {},
year = {},
note = {},
issn = {},
doi = {},
url = {},
author = {B{\"u}sch, Lukas and Palazo\u{g}lu, Mert and Sch{\"u}ppstuhl, Thorsten},
keywords = {Assembly, Human Action Recognition, Azure Kinect, Dataset, Artificial Intelligence, Methods-Time-Measurement}
}
```

## Abstract
Efficient production of green electrolyzers is crucial for transitioning to renewable energy sources. Human-Robot Collaboration (HRC) can optimize processes, ensuring efficiency and safety. This paper presents a novel dataset to integrate human actions into digital twins, enhancing green electrolyzer production. Integrating humans into the digital process twin supports industry 5.0's human-centric manufacturing, building a database for further investigations and optimizations. Our research introduces a dataset for Human Action Recognition (HAR) in manufacturing, serving as a foundation for AI applications that integrate human activities into digital process twins. We developed a dataset of manual assembly processes using RGB, depth video, and skeleton data captured by an Azure Kinect, depicting humans in manual assembly processes.

## Setup / Hardware
- Workstation with sketch
- PC / GPI
- Azure Kinect
- Green Screen

## Data
- RGB 
    - Format
    - Resolution
- Depth
    - Format
    - Resolution
- Skeletal
    - Azure Kinect Body joints
        - from hip downwards only estimated due to occlusions
    - spatial-temporal graphs
- Folder structure
    - description and picture
    - contents
        - RGB_check
- Annotation / labeling
- task lists
    - task list 1
    - task list 2
    - task list 3
    - task list 4
    - task list 5

## Statistics


|                       |*Body Skeleton & Depth* ||| **RGB**                |||
| Tasks                 | SUM    | AVG    | STDEV  | SUM    | AVG    | STDEV  |
|-----------------------|--------|--------|--------|--------|--------|--------|
| Change head 1         | 49664  | 709.49 | 293.70 | 46727  | 718.88 | 301.86 |
| Change head 2         | 39502  | 564.31 | 156.61 | 36969  | 568.75 | 158.25 |
| Cutting w/ Knife      | 19285  | 459.17 | 122.84 | 17902  | 459.03 | 126.42 |
| Cutting w/ Scissors   | 18305  | 435.83 | 120.94 | 16781  | 430.28 | 123.41 |
| Drilling              | 84558  | 1207.97| 458.51 | 78020  | 1200.31| 472.73 |
| File                  | 27737  | 396.24 | 120.77 | 25756  | 396.25 | 124.18 |
| Hammering Nails       | 92421  | 1320.3 | 523.28 | 87358  | 1343.97| 531.30 |
| Hammering Punch       | 64104  | 915.77 | 259.10 | 59405  | 913.92 | 267.77 |
| Measure Diameter      | 47663  | 680.9  | 240.39 | 44370  | 682.62 | 248.29 |
| Measure Orthogonality | 34864  | 498.06 | 149.92 | 32118  | 494.12 | 154.74 |
| Take out w/ Plier     | 24897  | 355.67 | 99.31  | 23522  | 361.88 | 99.71  |
| Screw w/ drill        | 57365  | 819.5  | 329.14 | 53902  | 829.26 | 335.72 |
| Screw w/ Screwdriver  | 65929  | 941.84 | 265.64 | 61542  | 946.8  | 273.57 |
| Screw w/ hand         | 163626 | 779.17 | 240.42 | 153326 | 786.29 | 245.59 |
| Screw w/ allen key    | 53148  | 759.26 | 288.46 | 50355  | 774.69 | 288.76 |
| Screw w/ wrench       | 47237  | 665.31 | 191.58 | 44252  | 670.48 | 196.88 |
| Screw w/ ratchet      | 65491  | 949.14 | 460.20 | 61253  | 957.08 | 474.46 |
| Unscrew w/ drill      | 30358  | 433.69 | 163.48 | 28507  | 438.57 | 168.38 |
| Unscrew w/ Screwdriver| 35585  | 508.36 | 124.08 | 33678  | 518.12 | 123.35 |
| Unscrew w/ hand       | 65546  | 312.12 | 207.67 | 60736  | 311.47 | 214.47 |
| Unscrew w/ allen key  | 53476  | 763.94 | 312.81 | 50791  | 781.4  | 317.77 |
| Unscrew w/ wrench     | 51682  | 738.31 | 288.34 | 48940  | 752.92 | 293.29 |
| Unscrew w/ ratchet    | 56039  | 800.56 | 286.53 | 52724  | 811.14 | 294.59 |
| None                  | 23315  | 277.56 | 249.67 | 22308  | 286    | 256.87 |

|                       |*Body Skeleton & Depth* ||| **RGB**                |||
| Primitives            | SUM    | AVG    | STDEV  | SUM    | AVG    | STDEV  |
|-----------------------|--------|--------|--------|--------|--------|--------|
| Reach                 | 238226 | 108.28 | 85.19  | 223100 | 109.26 | 86.81  |
| Grasp                 | 66810  | 30.37  | 42.69  | 63149  | 30.93  | 43.79  |
| Move                  | 267565 | 72.63  | 72.07  | 247639 | 72.41  | 72.56  |
| Position              | 412588 | 149.65 | 173.64 | 389879 | 152.18 | 177.46 |
| Apply Pressure        | 355202 | 145.75 | 140.95 | 330568 | 146.01 | 143.29 |
| Release               | 33596  | 19.51  | 25.29  | 31556  | 19.73  | 25.92  |
| None                  | 44036  | 270.16 | 251.72 | 43109  | 272.84 | 255.17  |


## Data Access
We are working on a download link. For now, please rech out to the corresponding author via e-mail: [lukas.buesch@tuhh.de](mailto:lukas.buesch@tuhh.de?subject=HARDAT%20Download%20Request).

