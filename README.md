# RSPlace: Rotation Sensing Macro Placement via Bidirectional Tree Expansion

Tianyi Liu, Yaxin Xu, Lin Geng, Ningzhong Liu, Han Sun, Yu Wang

[Extended Version](Extended%20Version.pdf)

![Teaser](/imgs/RSPlace/RSPlace.png "Overview of RSPlace.")

## Visualization

Macro placement results on *adaptec2*.

|        Method         |     DREAMPlace [[1]](https://github.com/limbo018/DREAMPlace)     |     Graph Placement [[2]](https://www.nature.com/articles/s41586-021-03544-w)     |   DeepPR [[3]](https://github.com/Thinklab-SJTU/EDA-AI/tree/main/DeepPlace)   | MaskPlace [[4]](https://github.com/laiyao1/maskplace) |                            
|:---------------------:|:----------------------------------------------------------------:|:---------------------------------------------------------------------------------:|:-----------------------------------------------------------------------------:|:-----------------------------------------------------:|
|       Placement       |       <img src="imgs/DREAMPlace/adaptec2.png" width="160">       |                  <img src="imgs/Graph/adaptec2.png" width="160">                  |               <img src="imgs/DeepPR/adaptec2.png" width="160">                |  <img src="imgs/MaskPlace/adaptec2.png" width="160">  |
| HPWL (10<sup>5</sup>) |                              135.32                              |                                      359.35                                       |                                    197.13                                     |                         79.98                         |
|        Overlap        |                              0.16%                               |                                       1.54%                                       |                                    49.10%                                     |                           0                           |
|      **Method**       | **WireMask-EA** [[5]](https://github.com/lamda-bbo/WireMask-BBO) |  **EfficientPlace** [[6]](https://github.com/MIRALab-USTC/AI4EDA-EfficientPlace)  | **EA-Rotation** [[7]](https://ieeexplore.ieee.org/abstract/document/11037516) |                      **RSPlace**                      |
|       Placement       |        <img src="imgs/WireMask/adaptec2.png" width="160">        |             <img src="imgs/EfficientPlace/adaptec2.png" width="160">              |             <img src="imgs/EA-Rotation/adaptec2.png" width="160">             |   <img src="imgs/RSPlace/adaptec2.png" width="160">   |
| HPWL (10<sup>5</sup>) |                              55.32                               |                                       43.35                                       |                                     47.22                                     |                <strong>38.00</strong>                 |
|        Overlap        |                                0                                 |                                         0                                         |                                       0                                       |                           0                           |

## Mixed-size Placement

|                          *adaptec1*                          |                          *adaptec2*                          |                          *adaptec3*                          |                          *adaptec4*                          |                            
|:------------------------------------------------------------:|:------------------------------------------------------------:|:------------------------------------------------------------:|:------------------------------------------------------------:|
| <img src="imgs/RSPlace/Mixed-size/adaptec1.png" width="185"> | <img src="imgs/RSPlace/Mixed-size/adaptec2.png" width="185"> | <img src="imgs/RSPlace/Mixed-size/adaptec3.png" width="185"> | <img src="imgs/RSPlace/Mixed-size/adaptec4.png" width="185"> |
|                        ***bigblue1***                        |                        ***bigblue2***                        |                        ***bigblue3***                        |                        ***bigblue4***                        |
| <img src="imgs/RSPlace/Mixed-size/bigblue1.png" width="185"> | <img src="imgs/RSPlace/Mixed-size/bigblue2.png" width="185"> | <img src="imgs/RSPlace/Mixed-size/bigblue3.png" width="185"> | <img src="imgs/RSPlace/Mixed-size/bigblue4.png" width="185"> |

