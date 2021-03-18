# awesome-dynamic-slam

The following papers are the papers that fits my PhD research interest. They are mainly tackling the real-time reconstruction of multiplle dynamic objects or non-rigid objects. Some papers are off-line work yet also very interesting.

Due to my personal interests, SFM-based or factorization-based work are not collected here. Those papers can be found [here](https://github.com/openMVG/awesome_3DReconstruction_list).

Another related paper list is about the semantic segmentation, which can be found [here](https://github.com/mrgloom/awesome-semantic-segmentation).



------

## Related survey papers:

- State of the Art in Real-time Registration of RGB-D Images ([link](http://cg.cs.uni-bonn.de/aigaion2root/attachments/StateoftheArtinReal-timeRegistrationofRGB-DImages.pdf))
- Visual SLAM and Structure from Motion in Dynamic Environments: A Survey ([link](https://dl.acm.org/citation.cfm?id=3177853))
- State of the Art on 3D Reconstruction with RGB-D Cameras ([link](https://web.stanford.edu/~zollhoef/papers/EG18_RecoSTAR/paper.pdf))



## Multiple Rigid Object Tracking and Reconstruction (Real-time)

- Joint 3D Reconstruction of a Static Scene and Moving Objects (3DV 2017)
  - http://www.merl.com/publications/docs/TR2017-147.pdf (paper)
- Co-Fusion: Real-time Segmentation, Tracking and Fusion of Multiple Objects (ICRA 2017)
  - http://visual.cs.ucl.ac.uk/pubs/cofusion/ (website)
  - https://github.com/martinruenz/co-fusion (code)
  - http://visual.cs.ucl.ac.uk/pubs/cofusion/icra2017_co-fusion_print.pdf (paper)
  - Semantic segmentation is pre-computed


- MaskFusion (submitted to ISMAR 2018)

  - https://arxiv.org/pdf/1804.09194.pdf (paper)
  - http://visual.cs.ucl.ac.uk/pubs/maskfusion/ (website)
- Relevant: SE3-Nets: Learning Rigid Body Motion using Deep Neural Networks (ICRA 2017)

  - https://arxiv.org/pdf/1606.02378.pdf (paper)
  - Video: https://www.youtube.com/watch?v=UA_MKLHCWSo
- Learning Rigidity in Dynamic Scenes with a Moving Camera for 3D Motion Field Estimation (ECCV 2018)

  - paper: https://arxiv.org/abs/1804.04259
  - slides: http://on-demand.gputechconf.com/gtc/2018/presentation/s8798-learning-rigidity-in-dynamic-scenes-for-scene-flow-estimation-v2.pdf
  - video: https://www.youtube.com/watch?v=MnTHkOCY790&feature=youtu.be
  - web: http://research.nvidia.com/publication/2018-09_Learning-Rigidity-in
- SfM-Net: Learning of Structure and Motion from Video

  - https://arxiv.org/pdf/1704.07804.pdf
- Stereo Vision-based Semantic 3D Object and Ego-motion Tracking for Autonomous Driving (ECCV2018)


    - https://arxiv.org/pdf/1807.02062.pdf  (paper)
- Estimating metric poses of dynamic objects using monocular visual-inertial fusion (IROS 2018)


    - https://arxiv.org/pdf/1807.02062.pdf (paper)
  - Real-Time Object Pose Estimation with Pose Interpreter Networks (IROS2018)

      - https://arxiv.org/pdf/1808.01099.pdf (paper)
      - https://github.com/jimmyyhwu/pose-interpreter-networks (code)

  

## Non-rigid body Tracking and Reconstruction (Real-time)
http://www.liuyebin.com/4d.html


- DynamicFusion: Reconstruction and Tracking of Non-rigid Scenes in Real-Time (CVPR 2015)
  - http://grail.cs.washington.edu/projects/dynamicfusion/papers/DynamicFusion.pdf (paper)
- 3D Scanning Deformable Objects with a Single RGBD Sensor (CVPR 2015)
  - http://www.cs.unc.edu/~doums/pdfs/dkf.pdf (paper)
- VolumeDeform: Real-time Volumetric Non-rigid Reconstruction (ECCV2016)
  - https://graphics.stanford.edu/~niessner/papers/2016/5volumeDeform/innmann2016deform.pdf (paper)
- Fusion4D: Real-time Performance Capture of Challenging Scenes (Siggraph 2016)
  - http://www.samehkhamis.com/dou-siggraph2016.pdf (paper) 
- Real-time Geometry, Albedo and Motion Reconstruction Using a Single RGBD Camera (Siggraph 2017)
  - http://www.liuyebin.com/monofvv/monofvv_files/MonoFVV.pdf (paper)
  - http://www.liuyebin.com/monofvv/monofvv.html (website)
- KillingFusion: Non-rigid 3D Reconstruction without Correspondences (CVPR 2017)
  - http://campar.in.tum.de/pub/slavcheva2017cvpr/slavcheva2017cvpr.pdf (paper)
- SobolevFusion: 3D Reconstruction of Scenes Undergoing Free Non-rigid Motion (CVPR 2018)
  - http://campar.in.tum.de/pub/slavcheva2018cvpr/slavcheva2018cvpr.pdf (paper)
- MixedFusion: Real-Time Reconstruction of an Indoor Scene with Dynamic Objects (TVCG 2017)
  - http://feng-xu.com/papers/MixedFusion-tvcg.pdf (paper)
- DoubleFusion: Real-time Capture of Human Performances with Inner Body Shapes from a Single Depth Sensor (CVPR 2018)
  - http://www.liuyebin.com/doublefusion/doublefusion_files/doublefusion.pdf
  - http://www.liuyebin.com/doublefusion/doublefusion_files/DoubleFusion_SupVideo_CameraReady.mp4

## Background only, i.e. removing dynamic objects

- Fast Odometry and Scene Flow from RGB-D Cameras based on Geometric Clustering (ICRA 2017)
  - http://mapir.isa.uma.es/mjaimez/Papers/Jaimez_et_al_VOSF_2017.pdf (paper)
  - https://github.com/MarianoJT88/Joint-VO-SF (code)
  - http://mapir.isa.uma.es/mapirwebsite/index.php?option=com_content&view=article&layout=edit&id=241 (website)
- StaticFusion: Background Reconstruction for Dense RGB-D SLAM in Dynamic Environments (ICRA 2018)
  - http://www.robots.ox.ac.uk/~mobile/Papers/2018ICRA_scona.pdf (paper)
  - https://www.youtube.com/watch?v=UVsqIgxHoBM (video)
- Driven to Distraction: Self-Supervised Distractor Learning for Robust Monocular Visual Odometry in Urban Environments (ICRA 2018)
  - https://arxiv.org/pdf/1711.06623.pdf (paper)
- Detecting, Tracking and Eliminating Dynamic Objects in 3D Mapping using Deep Learning and Inpainting (ICRA 2018)
  - https://natanaso.github.io/rcw-icra18/assets/ref/ICRA-MRP18_paper_3.pdf (paper)


## Non-realtime: non-rigid reconstruction

- Video Pop-up : Monocular 3D Reconstruction of Dynamic Scenes SCENE RECONSTRUCTION WITH AN ADAPTIVE NEIGHBOURHOOD (ECCV 2014)
  - http://discovery.ucl.ac.uk/1454051/1/Russell_new_paper.pdf (paper)
  - https://github.com/cvfish/VideoPopup (code)
  - http://www0.cs.ucl.ac.uk/staff/R.Yu/video_popup/VideoPopup2.html (website)
- Robust Non-rigid Motion Tracking and Surface Reconstruction Using L0 Regularization (ICCV 2015)
  - http://media.au.tsinghua.edu.cn/liuyebin_files/nonrigid/nonrigid.pdf (paper)
  - Code available by sending mail to the author
  - http://media.au.tsinghua.edu.cn/nonrigid.html (website)





## Non-realtime: multiple object segmentation-tracking-reconstruction

- Dense Multibody Motion Estimation and Reconstruction from a Handheld Camera (ISMAR 2012)
  - https://www.doc.ic.ac.uk/~aroussos/RoussosRussellGargAgapito_DenseMultibody_ISMAR12.pdf (paper)
- Robust Dense Mapping for Large-Scale Dynamic Environments (ICRA 2018)
  - http://siegedog.com/dynslam/ (website)
  - http://siegedog.com/assets/dynslam/robust-dense-mapping-paper-submission.pdf (paper)
  - https://github.com/AndreiBarsan/DynSLAM (code)
  - pre-compute the semantic segmentation (cars)
- Multimotion Visual Odometry (MVO): Simultaneous Estimation of Camera and Third-Party Motions (IROS 2018)
  - https://arxiv.org/pdf/1808.00274.pdf (paper)





## Learn Depth and camera motion

- DeMoN: Depth and Motion Network for Learning Monocular Stereo

- Unsupervised Learning of Depth and Ego-Motion from Video

- Multi-view Supervision for Single-view Reconstructionvia Differentiable Ray Consistency

  

  

## Learn 3D map

- OctNet: Learning Deep 3D Representations at High Resolutions
