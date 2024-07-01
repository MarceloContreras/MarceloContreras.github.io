I am currently a Master's student at University of Alberta working with Professor [Ehsan Hashemi](https://apps.ualberta.ca/directory/person/ehashemi) as part of the [NODE Lab](https://sites.google.com/view/ehsan-hashemi-uwaterloo/home). My research intends to develop *reliable autonomous navigation systems* for *adversarial scenarios* (dynamic surrondings, light conditions and weather) and lies as a mixture of **SLAM**, **Graph Optimization**, **Deep Learning (DL)** and **State Estimation**. I started at NODE Lab as visiting scholar in 2023, supported by the [ELAP](https://www.educanada.ca/scholarships-bourses/can/institutions/elap-pfla.aspx?lang=eng) scholarship granted by Canadian government. 

Previously, I received my Bachelor's degree in Mechatronics Engineering with a minor in robotics from the Universidad de Ingenieria y Tecnologia, Lima, Peru in 2023. My thesis was focused on *electroencephalography (EEG) decoding* for stimulus prediction through a **Transformer DNN** fused with **Interval Fuzzy Type-2 (IFT2)** units that can handle uncertainties and improve predictions, and it was supervised by Professor [Christian Flores](https://scholar.google.com/citations?user=kHwwJn4AAAAJ&hl=pt-BR)

<p align="center">
  <a href="https://scholar.google.com/citations?user=nUF0J2IAAAAJ&hl=es">Google Scholar</a>, <a href="https://www.linkedin.com/in/marcelo-contreras-cabrera/">Linkedin</a>, <a href="/assets/Resume.pdf">CV</a>
</p>


## Education

* M.S Mechanical. Eng, University of Alberta, Canada (now)
* B.S Mechatronics. Eng, Universidad de Ingenieria y Tecnologia, Peru (2019-2023)

## News
* **July 2024: Paper accepted@IEEE T-NSRE:** Our work on [Transfer Learning with Active Sampling for Rapid Training and Calibration in BCI-P300 Across Health States and Multi-centre Data](https://ieeexplore.ieee.org/document/10578037) was accepted to IEEE T-NSRE
* **June 2024: Paper accepted@IEEE T-IV:** Our work on [DynaNav-SVO: Dynamic Stereo Visual Odometry With Semantic-Aware Perception for Autonomous Navigation](https://ieeexplore.ieee.org/abstract/document/10561598/) was accepted to IEEE T-IV
* **April 2024** I am member of the organizing committee of [IEEE ITSC 2024](https://ieee-itsc.org/2024/)
* **March 2024: <code style="color : green">Accepted as Master's student</code>** in University of Alberta under the supervision of Professor [Ehsan Hashemi](https://apps.ualberta.ca/directory/person/ehashemi) as part of his laboratory (NODE Lab).
* **February 2024: Paper accepted@Frontiers:** Our work on [A Survey on 3D Object Detection in Real Time for Autonomous Driving](https://www.frontiersin.org/articles/10.3389/frobt.2024.1212070/full) was accepted to Frontiers in Robotics and AI Journal. 
* **January 2024: Paper submitted@T-NSRE** Our work on *Transfer Learning Cross-domain with Active Sampling for Rapid Training in BCI-P300* was submitted to IEEE Transactions on Neural Systems and Rehabilitation Engineering (T-NSRE).
* **December 2024: <code style="color : green">Defended Bachelor Thesis</code>** about uncertainty robustness in SSVEP classification by a Fuzzy-Transformer DNN. 
* **August 2023: Paper accepted@ITSC 2023** Our work on [A Stereo Visual Odometry Framework with Augmented Perception for Dynamic Urban Environments](https://ieeexplore.ieee.org/abstract/document/10421981) was accepted to IEEE ITSC 2023 as a regular conference paper.
* **January 2023: Research intership** is funded with <code style="color : orange">ELAP</code> scholarship granted by the Global Affairs Canada’s International Scholarships Program. Worked with Professor [Ehsan Hashemi](https://apps.ualberta.ca/directory/person/ehashemi) in the NODE Lab at University of Alberta. 


## Publications

### [Transfer Learning with Active Sampling for Rapid Training and Calibration in BCI-P300 Across Health States and Multi-centre Data](https://ieeexplore.ieee.org/document/10578037)
[Christian Flores](https://scholar.google.com/citations?user=kHwwJn4AAAAJ&hl=pt-BR); Marcelo Contreras; Ichiro Macedo; [Javier Andreu-Perez](https://scholar.google.com/citations?user=1m4DHQQAAAAJ&hl=en) 

*IEEE Transactions on Neural Systems and Rehabilitation Engineering*

Machine learning and deep learning advancements have boosted Brain-Computer Interface (BCI) performance, but their wide-scale applicability is limited due to factors like individual health, hardware variations, and cultural differences affecting neural data. Studies often focus on uniform single-site experiments in uniform settings, leading to high performance that may not translate well to real-world diversity. Deep learning models aim to enhance BCI classification accuracy, and transfer learning has been suggested to adapt models to individual neural patterns using a base model trained on others’ data. This approach promises better generalizability and reduced overfitting, yet challenges remain in handling diverse and imbalanced datasets from different equipment, subjects, multiple centres in different countries, and both healthy and patient populations for effective model transfer and tuning. In a setting characterized by maximal heterogeneity, we proposed P300 wave detection in BCIs employing a convolutional neural network fitted with adaptive transfer learning based on Poison Sampling Disk (PDS) called Active Sampling (AS), which flexibly adjusts the transition from source data to the target domain. Our results reported for subject adaptive with 40% of adaptive fine-tuning that the averaged classification accuracy improved by 5.36% and standard deviation reduced by 12.22% using two distinct, internationally replicated datasets. These results outperformed in classification accuracy, computational time, and training efficiency, mainly due to the proposed Active Sampling (AS) method for transfer learning.

### [DynaNav-SVO: Dynamic Stereo Visual Odometry With Semantic-Aware Perception for Autonomous Navigation](https://ieeexplore.ieee.org/abstract/document/10561598/)
Marcelo Contreras; [Neel Pratik Bhatt](https://scholar.google.com/citations?user=S8ofWDUAAAAJ&hl=en); [Ehsan Hashemi](https://scholar.google.com/citations?user=-9MfEXMAAAAJ&hl=en)

*IEEE Transactions on Intelligent Vehicles*

Conventional visual navigation methods presume scene stability and encounter challenges due to moving objects in highly dynamic environments. We propose DynaNav-SVO, a stereo visual odometry (VO) framework, which semantically detects and constructs a region-of-interest (ROI) by focusing on a-priori urban fixed elements for reliable feature extraction and subsequently estimates vehicle pose. The outcome is a static map with minimal outliers and is used for state estimation in dynamic scenes and perceptually degraded conditions. This map enhances computational efficiency due to the reduced size of the new static mask (as confirmed in several experiments), compared to the existing visual simultaneous localization and mapping (vSLAM) solutions. To refine the estimated pose, a back-end module selects a moving horizon of frames, generates a covisibility graph for data association, and optimizes a structure-from-motion program using local bundle adjustment. Finally, the performance of the framework is experimentally evaluated using a test vehicle in highly-dynamic urban settings and under adverse weather conditions with degraded visual perception with varying sequence lengths. The experiments confirm excellent performance in terms of estimation accuracy and computational efficiency for autonomous navigation compared to existing vSLAM methods.

### [A Survey on 3D Object Detection in Real Time for Autonomous Driving](https://www.frontiersin.org/articles/10.3389/frobt.2024.1212070/full)
Marcelo Contreras; Aayush Jain; [Neel Pratik Bhatt](https://scholar.google.com/citations?user=S8ofWDUAAAAJ&hl=en); [Arunava Banerjee](https://scholar.google.co.in/citations?user=Bol-rwwAAAAJ&hl=en); [Ehsan Hashemi](https://scholar.google.com/citations?user=-9MfEXMAAAAJ&hl=en)

*Frontiers in Robotics and AI (2024)*

This survey reviews the state-of-the-art 3D object detection techniques that utilizes monocular and stereo vision for reliable detection in urban settings. Based on depth inference basis, learning schemes, and internal representation, this work presents a method taxonomy of three classes: model-based and geometrically constrained approaches, end-to-end learning methodologies, and hybrid methods To prove the effectiveness of each method, 3D object detection datasets for autonomous vehicles are described with their unique features, e. g., varying weather conditions, multi-modality, multi camera perspective and their respective metrics associated to different difficulty categories. In addition, we included multi-modal visual datasets, i. e., V2X that may tackle the problems of single-view occlusion.

### [A Stereo Visual Odometry Framework with Augmented Perception for Dynamic Urban Environments](https://ieeexplore.ieee.org/abstract/document/10421981)

Marcelo Contreras; [Neel Pratik Bhatt](https://scholar.google.com/citations?user=S8ofWDUAAAAJ&hl=en); [Ehsan Hashemi](https://scholar.google.com/citations?user=-9MfEXMAAAAJ&hl=en)

*Intelligent Transportation Systems Conference (ITSC) (2023)*

One of main challenges of Visual Simultaneous Localization and Mapping (vSLAM) for navigation of mobile robots or automated driving systems is operating reliably in highly dynamic environments while assuming scene rigidity. In this paper, we propose a semantic-aware stereo visual odometry framework wherein feature extraction is performed over a static region-of-interest (ROI) generated through object detection and instance segmentation on a priori static street objects. This process generates a set of reliable features and a static map for pose estimation. Furthermore, the size of these quantities is downsized compared to a regular vSLAM map generation to reduce computational costs without compromising accuracy. A temporal window for pose estimation is also proposed to construct a covisibility graph and refine the pose estimation in a local bundle adjustment scheme; computational cost of the framework is also investigated in several driving scenarios. Extensive real driving sequences in various dynamic urban environments with varying sequence lengths confirms excellent performance and computational efficiency of the proposed bundle adjustment scheme using semantic-aware feature tracking compared to state-of-the-art approaches.
