# Awesome Bird's Eye View Perception
This is a repository for Bird's Eye View Perception, including 3D object detection, segmentation, online-mapping and occupancy prediction.

## News
```
- 2023.05.09: An initial version of recent papers or projects.
```

## Contents

## Papers
- [Survey](#survey)
- [3D Object Detection](#3d-object-detection) 
  - [Monocular](#monocular)
  - [Multiple Camera](#multiple-camera)
- [BEV Segmentation](#bev-segmentation)
  - [Monocular](#monocular)
  - [Multiple Camera](#multiple-camera)
- [Mapping](#mapping)
- [Occupancy Prediction](#occupancy-prediction)

### Survey
- Vision-Centric BEV Perception: A Survey (Arxiv 2022)[[Paper]](https://arxiv.org/abs/2208.02797) [[Github]](https://github.com/4DVLab/Vision-Centric-BEV-Perception)
- Delving into the Devils of Bird’s-eye-viewPerception: A Review, Evaluation and Recipe (Arxiv 2022) [[Paper]](https://arxiv.org/abs/2209.05324) [[Github]](https://github.com/OpenDriveLab/BEVPerception-Survey-Recipe)
### 3D Object Detection
#### Monocular
- Learning  2D  to  3D  Lifting  for  Object  Detection  in  3Dfor  Autonomous  Vehicles (IROS 2019) [[Paper]](https://arxiv.org/abs/1904.08494) [[Project Page](https://www.nec-labs.com/research/media-analytics/projects/learning-2d-to-3d-lifting-for-object-detection-in-3d-for-autonomous-vehicles/)
- Orthographic Feature Transform for Monocular 3D Object Detection (BMVC 2019) [[Paper]](http://mi.eng.cam.ac.uk/~cipolla/publications/inproceedings/2019-BMVC-Orthographic-Feature-Transform.pdf) [[Github]](https://github.com/tom-roddick/oft)
- BEV-MODNet: Monocular Camera-based Bird's Eye View Moving Object Detection for Autonomous Driving (ITSC 2021) [[Paper]](https://arxiv.org/abs/2107.04937) [[Project Page]](https://sites.google.com/view/bev-modnet)
- Categorical Depth Distribution Network for Monocular 3D Object Detection (CVPR 2021) [[Paper]](https://openaccess.thecvf.com/content/CVPR2021/papers/Reading_Categorical_Depth_Distribution_Network_for_Monocular_3D_Object_Detection_CVPR_2021_paper.pdf) [[Github]](https://github.com/TRAILab/CaDDN)
- PersDet: Monocular 3D Detection in Perspective Bird’s-Eye-View (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2208.09394.pdf)
#### Multiple Camera
- BEVDet: High-Performance Multi-Camera 3D Object Detection in Bird-Eye-View (Arxiv 2022) [[Paper]](https://arxiv.org/abs/2112.11790) [[Github]](https://github.com/HuangJunJie2017/BEVDet)
- DETR3D：3D Object Detection from Multi-view Image via 3D-to-2D Queries (CORL 2021) [[Paper]](https://arxiv.org/abs/2110.06922) [[Github]](https://github.com/WangYueFt/detr3d)
- BEVFusion: A Simple and Robust LiDAR-Camera Fusion Framework (NeurIPS 2022) [[Paper]](https://arxiv.org/abs/2205.13790)[[Github]](https://github.com/ADLab-AutoDrive/BEVFusion)
- Polar Parametrization for Vision-based Surround-View 3D Detection (arxiv 2022) [[Paper]](https://arxiv.org/abs/2206.10965) [[Github]](https://github.com/hustvl/PolarDETR)
- SRCN3D: Sparse R-CNN 3D Surround-View Camera Object Detection andTracking for Autonomous Driving  (Arxiv 2022) [[Paper]](https://arxiv.org/abs/2206.14451) [[Github]](https://github.com/synsin0/SRCN3D)
- BEVDet4D: Exploit Temporal Cues in Multi-camera 3D Object Detection (Arxuv 2022) [[Paper]](https://arxiv.org/pdf/2203.17054.pdf) [[Github]](https://github.com/HuangJunJie2017/BEVDet)
- BEVStereo: Enhancing Depth Estimation in Multi-view 3D Object Detection withDynamic Temporal Stere (Arxiv 2022) [[Paper]](https://arxiv.org/abs/2209.10248)[[Github]](https://github.com/Megvii-BaseDetection/BEVStereo)
- CRAFT: Camera-Radar 3D Object Detectionwith Spatio-Contextual Fusion Transformer (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2209.06535.pdf)
- MV-FCOS3D++: Multi-View Camera-Only 4D Object Detection with Pretrained Monocular Backbones (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2207.12716.pdf) [[Github]](https://github.com/Tai-Wang/Depth-from-Motion)
- DETR4D: Direct Multi-View 3D Object Detection with Sparse Attention (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2212.07849.pdf)
- SemanticBEVFusion: Rethink LiDAR-Camera Fusion in Unified Bird's-Eye View Representation for 3D Object Detectio (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2212.04675.pdf)
- BEV-SAN: Accurate BEV 3D Object Detection via Slice Attention Networks (Arxiv 2022) [[Paper]](https://arxiv.org/pdf/2212.04675.pdf)
- AutoAlign: Pixel-Instance Feature Aggregationfor Multi-Modal 3D Object Detection (IJCAI 2022) [[Paper]](https://www.ijcai.org/proceedings/2022/0116.pdf) 
- AutoAlignV2: Deformable Feature Aggregation for DynamicMulti-Modal 3D Object Detection (ECCV 2022) [[Paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136680616.pdf)[[Github]](https://github.com/zehuichen123/AutoAlignV2)
- CenterFormer: Center-based Transformer for 3D Object Detection (ECCV 2022) [[paper]](https://www.ecva.net/papers/eccv_2022/papers_ECCV/papers/136980487.pdf)[[Github]](https://github.com/TuSimple/centerformer)
- STS: Surround-view Temporal Stereo for Multi-view 3D Detection (Arxiv 2022) [[Paper]](https://arxiv.org/abs/2208.10145)
- BEVDepth: Acquisition of Reliable Depth forMulti-view 3D Object Detection (AAAI 2023) [[Paper]](https://arxiv.org/abs/2206.10092) [[Github]](https://github.com/Megvii-BaseDetection/BEVDepth)
- PolarFormer: Multi-camera 3D Object Detectionwith Polar Transformers (AAAI 2023) [[Paper]](https://arxiv.org/abs/2206.15398)[[Github]](https://github.com/fudan-zvg/PolarFormer)
- A Simple Baseline for Multi-Camera 3D Object Detection (AAAI 2023) [[Paper]](https://arxiv.org/abs/2208.10035)[[Github]](https://github.com/zhangyp15/SimMOD)
- MGTANet: Encoding Sequential LiDAR Points Using Long Short-Term Motion-Guided Temporal Attention for 3D Object Detection (AAAI 2023)[[paper]](https://arxiv.org/pdf/2212.00442.pdf)[[Github]](https://github.com/HYjhkoh/MGTANet)
- Cross Modal Transformer via Coordinates Encoding for 3D Object Dectection (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2301.01283.pdf) [[Github]](https://github.com/junjie18/CMT)
- Sparse4D: Multi-view 3D Object Detection with Sparse Spatial-Temporal Fusion (Arxiv 2023) [[Paper]](https://arxiv.org/pdf/2211.10581.pdf) [[Github]](https://github.com/linxuewu/Sparse4D)
- SOLOFusion: Time Will Tell: New Outlooks and A Baseline for Temporal Multi-View 3D Object Detection (ICLR 2023) [[paper]](https://arxiv.org/abs/2210.02443)[[Github]](https://github.com/Divadi/SOLOFusion)
- BEVDistill: Cross-Modal BEV Distillation for Multi-View 3D Object Detection (ICLR 2023) [[Paper]](https://openreview.net/pdf?id=-2zfgNS917)[[Github]](https://github.com/zehuichen123/BEVDistill)
- 
### BEV Segmentation
#### Monocular
#### Multiple Camera
### Mapping
### Occupancy Prediction 
