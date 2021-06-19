# Welcome to my homepage!

Just finished Master's thesis defense, waiting for graduate and packing myself home.

<center>
<figure>
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/dev/pictures/thesis_defense.jpg" height="240" />
</figure>
</center>



## Introduction
I am Yan Dong. I got my bachelor degree (Automation) from Beijing Institute of Technology (BIT) in 2018, now I will graduate from Tsinghua University (THU) soon and be a PhD candidate in HUST. My research interests are SLAM & event-based cameras. 

## Publication

- Standard and Event Cameras Fusion for Feature Tracking. Yan Dong and Tao Zhang. The 4th International Conference on Machine Vision and Applications, 2021 (Accepted)
- A Real Time Algorithm for Multiple Data Matrix Codes Localization. Yan Dong and Tao Zhang. 2020 International Conference on Guidance, Navigation and Control (ICGNC 2020), Tianjin, China, October 23-25, 2020
- A Novel Cane with Camera to Locate Tactile Paving. The 12th IFAC Conference on Control Applications in Marline Systems, Robotics, and Vehicles, in Daejeon Korea, Sep 2019



## Research 

#### Event-based feature tracking
Proposed a new algorithm using both event-based camera and standard cameras for feature tracking. Source codes will be released soon.
<center>
<figure>
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/dev/pictures/eb_tracking.png" />
</figure>
</center>

#### Event-based dense mapping
Using both event-based camera and standard cameras for mapping. Due to the nature of event cameras, event-based mapping is sparse/semi-dense edge map. Frames can be used to generate dense map. In this work I attempt to use segmentations on frames to fill depths in edge map. I will continue to work on this method if time permits. Paper on arXiv: [https://arxiv.org/abs/2102.03567](https://arxiv.org/abs/2102.03567). If you have any ideas to improve this method, please contact me.
<center>
<figure>
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/dev/pictures/eb_mapping.png" />
</figure>
</center>




## Project


#### Coal mining support 3D reconstruction (Almost finished)
Reconstruct hydraulic pressure supports in mine. Two LiDARs are used for localization and reconstruction. After reconstruction, each support is isolated and states (position&orientation) of the sprag (护帮)  and base are detected for its control. Now we are waiting for Mining Products Safety Approval and Certification to test our algorithm in a real mine. 
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
Deleloped a robust and real-time algorithm to localize datamatrix tags on ground. The algorithm runs in rasberry pi 4 with up to 40fps. The scanner prototype was used in many applications of our partners, but today they are using scanners from DaHeng which costs less money and efforts.  :(
<center>
<figure>
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/dev/pictures/agv1.bmp" height="240" />
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/dev/pictures/agv2.bmp" height="240" />
</figure>
</center>







