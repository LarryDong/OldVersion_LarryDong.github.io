# Welcome to my homepage!

This homepage is just created and I am new to github pages. It looks ugly now I know, but it will be better.


## Introduction
I am Yan Dong. I got my bachelor degree (Automation) from Beijing Institute of Technology (BIT) in 2018, now I am a master's student in Tsinghua University (THU). My research interests are SLAM & event-based cameras. My updated CV can be found [here].

## Publication

- Standard and Event Cameras Fusion for Feature Tracking. Yan Dong and Tao Zhang. The 4th International Conference on Machine Vision and Applications, 2021 (Accepted)
- A Real Time Algorithm for Multiple Data Matrix Codes Localization. Yan Dong and Tao Zhang. 2020 International Conference on Guidance, Navigation and Control (ICGNC 2020), Tianjin, China, October 23-25, 2020
- A Novel Cane with Camera to Locate Tactile Paving. The 12th IFAC Conference on Control Applications in Marline Systems, Robotics, and Vehicles, in Daejeon Korea, Sep 2019



## Research 

#### Event-based feature tracking
Proposed a new algorithm using both event-based camera and standard cameras for feature tracking. Source codes will be released soon. **Source code is released!** [here](https://github.com/LarryDong/FusionTracking)
<center>
<figure>
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/dev/pictures/eb_tracking.png" />
</figure>
</center>

#### Event-based dense mapping
Using both event-based camera and standard cameras for mapping. Due to the nature of event cameras, event-based mapping is sparse/semi-dense edge map. Frames can be used to generate dense map. In this work I attempt to use segmentations on frames to fill depths in edge map. I will continue to work on this method if time permits. Paper on arXiv: [https://arxiv.org/abs/2102.03567](https://arxiv.org/abs/2102.03567).
<center>
<figure>
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/dev/pictures/eb_mapping.png" />
</figure>
</center>




## Project


#### Coal mining support 3D reconstrction (In process)
Reconstruct hydraulic pressure supports in mine. Two LiDARs are used for localization and reconstruction. After reconstruction, each support is isolated based on protecting board on the top. Futher work is to calcualte poses and show the model of suppots in mine.
<center>
<figure>
<!--
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/dev/pictures/zmj1.png" height="240" />
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/dev/pictures/zmj2.png" height="240" />
-->
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/dev/pictures/zmj_slam.png" height="240" />
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/dev/pictures/zmj_segmentation.png" height="240" />
</figure>
</center>


#### AGV scanner (Finished)
Deleloped a robust and real-time algorithm to localize datamatrix tags on ground. The algorithm runs in rasberry pi 4 with up to 40fps. The scanner prototype is now used in many applications of our partners.
<center>
<figure>
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/dev/pictures/agv1.bmp" height="240" />
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/dev/pictures/agv2.bmp" height="240" />
</figure>
</center>







