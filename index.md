# Homepage of Yan (Larry) Dong

## Introduction
Yan Dong (PhD Student)

*State Key Lab of Digital Manufacturing Equipment and Technology*  
Huazhong University of Science and Technology (HUST), China.   


## Publication

- Y. Dong et al., "Roof Supports Measurement in Coal Mining by 3D Registration and Model Fitting," 2021 China Automation Congress (CAC), 2021, pp. 2494-2497. [Paper](https://ieeexplore.ieee.org/document/9728663), [Poster](https://www.researchgate.net/publication/356494533_Roof_Supports_Measurement_in_Coal_Mining_by_3D_Registration_and_Model_Fitting)
- Yan Dong and Tao Zhang. 2021. Standard and Event Cameras Fusion for Feature Tracking. In 2021 International Conference on Machine Vision and Applications (ICMVA 2021). Association for Computing Machinery, New York, NY, USA, 55–60.[Paper](https://dl.acm.org/doi/abs/10.1145/3459066.3459075), [Code](https://github.com/LarryDong/FusionTracking) 
- Dong Y., Zhang T. (2022) A Real-Time Algorithm for Multiple Data Matrix Codes Localization. In: Yan L., Duan H., Yu X. (eds) Advances in Guidance, Navigation and Control. Lecture Notes in Electrical Engineering, vol 644. Springer, Singapore. [Paper](https://link.springer.com/chapter/10.1007/978-981-15-8155-7_208)



## Research 

#### Event-based feature tracking
Proposed a new algorithm using both event-based camera and standard cameras for feature tracking.  
Paper avaliable: [Standard and Event Cameras Fusion for Feature Tracking](https://dl.acm.org/doi/abs/10.1145/3459066.3459075)  
Source code released: [Here](https://github.com/LarryDong/FusionTracking)

<center>
<figure>
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/main/pictures/eb_tracking.png" />
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
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/main/pictures/zmj1.png" height="240" />
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/main/pictures/zmj2.png" height="240" />
-->
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/main/pictures/zmj_slam.png" height="240" />
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/main/pictures/zmj_segmentation.png" height="240" />
</figure>
</center>


#### AGV scanner (Finished)
Deleloped a robust and real-time algorithm to localize datamatrix tags on ground. The algorithm runs in rasberry pi 4 with up to 40fps. The scanner prototype was used in many applications of our partners, but today they are using scanners from DaHeng which costs less money and efforts.  :(
<center>
<figure>
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/main/pictures/agv1.bmp" height="240" />
<img src="https://raw.githubusercontent.com/LarryDong/LarryDong.github.io/main/pictures/agv2.bmp" height="240" />
</figure>
</center>







