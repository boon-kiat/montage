## Astronomical Image Mosaic Engine Using Distributed Computing Architecture

### Module:
WQD7008 Parallel and Distributed Computing 

### Group Members:
| Name | Matric ID|
| ---------------------- |:--------:|
| Chan Tzyy Yan | 17153472 |
| Choo En Ming | 22079929 |
| Low Boon Kiat | 17138399 |
| Yeoh Joer | 22077700 |
| Zhou Yao | S2177633 |

### Problem Statement:
Montage is a scientific workflow for generating astronomical images mosaic. By integrating multiple images into a single mosaic, Montage enables astronomers to study various celestial objects such as galaxies and nebulae comprehensively. Montage workflow involves complex tasks such as image re-projection and background rectification with strong demand for extensive computational resources and efficient data handling. The intricate nature of Montage's workflow, involving large volume of astronomical images and critical task dependencies, underscores the necessity for distributed computing to execute these tasks efficiently.

### Objective:
- To design a distributed data processing platform using Amazon Web Services (AWS), leveraging HTCondor as the resource management and task scheduler, NFS as the distributed data management system, and HTCondor DAGMan as the workflow management engine within the AWS environment.
- To employ Montage, a scientific workflow known for generating astronomical image mosaic, as the use case to enact on the established platform.
- To evaluate the performance of the established platform by executing Montage workflow under varying conditions and identify limitations of the deployed distributed data processing platform.

### Dataset:
- M8, M15 and M17 images obtained from [NASA/IPAC Infrared Science Archive](https://archive.ph/AWa3I#selection-135.0-135.33)

### Cloud Computing Platform:
- Amazon Web Services

### Methodology:
- [HTCondor Configuration and Setup](https://github.com/yjoer/htcondor-cluster)
- [Montage Workflow](https://github.com/yjoer/montage)
