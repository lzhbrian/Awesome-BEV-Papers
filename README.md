# Awesome-BEV-Papers
curated list of BEV related papers. I also organized DETR related papers here, as they are also closely related to most recent papers.

I am intensely reading BEV related papers these days, so this list is expected to be updated very frequently.

### TOC
* [Survey](#survey)
* [BEV 3D Object Detection](#bev-3d-object-detection-related) (mainly camera and camera+lidar based)
* [BEV Segmentation](#bev-segmentation-related) (mainly camera and camera+lidar based)
* [LiDAR](#lidar)
* [DETR Series](#detr-series)

### Survey
- Delving into the Devils of Bird's-eye-view Perception: A Review, Evaluation and Recipe.<br>
Hongyang Li, Chonghao Sima, Jifeng Dai, Wenhai Wang, Lewei Lu, Huijie Wang, Enze Xie, Zhiqi Li, Hanming Deng, Hao Tian, Xizhou Zhu, Li Chen, Yulu Gao, Xiangwei Geng, Jia Zeng, Yang Li, Jiazhi Yang, Xiaosong Jia, Bohan Yu, Yu Qiao, Dahua Lin, Si Liu, Junchi Yan, Jianping Shi, Ping Luo.<br>
In . [[2209.05324](https://arxiv.org/abs/2209.05324)] [[OpenPerceptionX/BEVPerception-Survey-Recipe](https://github.com/OpenPerceptionX/BEVPerception-Survey-Recipe)]
- Vision-Centric BEV Perception: A Survey<br>
Yuexin Ma, Tai Wang, Xuyang Bai, Huitong Yang, Yuenan Hou, Yaming Wang, Yu Qiao, Ruigang Yang, Dinesh Manocha, Xinge Zhu.<br>
In . [[2208.02797](https://arxiv.org/abs/2208.02797)] [[4DVLab/Vision-Centric-BEV-Perception](https://github.com/4DVLab/Vision-Centric-BEV-Perception)]
- 3D Object Detection for Autonomous Driving: A Review and New Outlooks<br>
Jiageng Mao, Shaoshuai Shi, Xiaogang Wang, Hongsheng Li.<br>
In . [[2206.09474](https://arxiv.org/abs/2206.09474)] [[PointsCoder/Awesome-3D-Object-Detection-for-Autonomous-Driving](https://github.com/PointsCoder/Awesome-3D-Object-Detection-for-Autonomous-Driving)]


### BEV 3D Object Detection related
(mainly camera and camera+lidar based)
- **[HMFI]** Homogeneous Multi-modal Feature Fusion and Interaction for 3D Object Detection<br>
Xin Li, Botian Shi, Yuenan Hou, Xingjiao Wu, Tianlong Ma, Yikang Li, Liang He.<br>
In ECCV 2022. [[2210.09615](https://arxiv.org/abs/2210.09615)]
- **[SOLOFusion]** Time Will Tell: New Outlooks and A Baseline for Temporal Multi-View 3D Object Detection<br>
Jinhyung Park, Chenfeng Xu, Shijia Yang, Kurt Keutzer, Kris Kitani, Masayoshi Tomizuka, Wei Zhan.<br>
In . [[2210.02443](https://arxiv.org/abs/2210.02443)] [[Divadi/SOLOFusion](https://github.com/Divadi/SOLOFusion)]
- **[BEVDistill]** BEVDistill: Cross-modal BEV Distillation For Multi-view 3D Object Detection.<br>
Anonymous.<br>
In ICLR 2023 (submission). [[paper](https://openreview.net/forum?id=-2zfgNS917)]
- **[SpatialDETR]** SpatialDETR: Robust Scalable Transformer-Based 3D Object Detection from Multi-View Camera Images with Global Cross-Sensor Attention.<br>
Simon Doll, Richard Schulz, Lukas Schneider, Viviane Benzin, Markus Enzweiler, Hendrik P.A. Lensch.<br>
In ECCV 2022. [[paper](https://markus-enzweiler.de/downloads/publications/ECCV2022-spatial_detr.pdf)] [[cgtuebingen/SpatialDETR](https://github.com/cgtuebingen/SpatialDETR)]
- **[CrossDTR]** CrossDTR: Cross-view and Depth-guided Transformers for 3D Object Detection<br>
Ching-Yu Tseng, Yi-Rong Chen, Hsin-Ying Lee, Tsung-Han Wu, Wen-Chin Chen, Winston Hsu.<br>
In . [[2209.13507](https://arxiv.org/abs/2209.13507)] [[sty61010/CrossDTR](https://github.com/sty61010/CrossDTR)]
- **[CFF]** Center Feature Fusion: Selective Multi-Sensor Fusion of Center-based Objects<br>
Philip Jacobson, Yiyang Zhou, Wei Zhan, Masayoshi Tomizuka, Ming C. Wu.<br>
In . [[2209.12880](https://arxiv.org/abs/2209.12880)]
- **[DeepFusion]** DeepFusion: A Robust and Modular 3D Object Detector for Lidars, Cameras and Radars<br>
Florian Drews, Di Feng, Florian Faion, Lars Rosenbaum, Michael Ulrich, Claudius Gläser.<br>
In . [[2209.12729](https://arxiv.org/abs/2209.12729)]
- **[BEVStereo]** BEVStereo: Enhancing Depth Estimation in Multi-view 3D Object Detection with Dynamic Temporal Stereo<br>
Yinhao Li, Han Bao, Zheng Ge, Jinrong Yang, Jianjian Sun, Zeming Li.<br>
In . [[2209.10248](https://arxiv.org/abs/2209.10248)] [[Megvii-BaseDetection/BEVStereo](https://github.com/Megvii-BaseDetection/BEVStereo)]
- **[MSMDFusion]** MSMDFusion: Fusing LiDAR and Camera at Multiple Scales with Multi-Depth Seeds for 3D Object Detection<br>
Yang Jiao, Zequn Jie, Shaoxiang Chen, Jingjing Chen, Xiaolin Wei, Lin Ma, Yu-Gang Jiang.<br>
In . [[2209.03102](https://arxiv.org/abs/2209.03102)]
- **[DeepInteraction]** DeepInteraction: 3D Object Detection via Modality Interaction<br>
Zeyu Yang, Jiaqi Chen, Zhenwei Miao, Wei Li, Xiatian Zhu, Li Zhang.<br>
In . [[2208.11112](https://arxiv.org/abs/2208.11112)]
- **[STS]** STS: Surround-view Temporal Stereo for Multi-view 3D Detection<br>
Zengran Wang, Chen Min, Zheng Ge, Yinhao Li, Zeming Li, Hongyu Yang, Di Huang.<br>
In . [[2208.10145](https://arxiv.org/abs/2208.10145)]
- **[SimMOD]** A Simple Baseline for Multi-Camera 3D Object Detection<br>
Yunpeng Zhang, Wenzhao Zheng, Zheng Zhu, Guan Huang, Jie Zhou, Jiwen Lu.<br>
In . [[2208.10035](https://arxiv.org/abs/2208.10035)] [[zhangyp15/SimMOD](https://github.com/zhangyp15/SimMOD)]
- **[PersDet]** PersDet: Monocular 3D Detection in Perspective Bird's-Eye-View<br>
Hongyu Zhou, Zheng Ge, Weixin Mao, Zeming Li.<br>
In . [[2208.09394](https://arxiv.org/abs/2208.09394)]
- **[DfM]** Monocular 3D Object Detection with Depth from Motion<br>
Tai Wang, Jiangmiao Pang, Dahua Lin.<br>
In ECCV 2022. [[2207.12988](https://arxiv.org/abs/2207.12988)] [[Tai-Wang/Depth-from-Motion](https://github.com/Tai-Wang/Depth-from-Motion)]
- **[MV-FCOS3D++]** MV-FCOS3D++: Multi-View Camera-Only 4D Object Detection with Pretrained Monocular Backbones<br>
Tai Wang, Qing Lian, Chenming Zhu, Xinge Zhu, Wenwei Zhang.<br>
In . [[2207.12716](https://arxiv.org/abs/2207.12716)] [[Tai-Wang/Depth-from-Motion](https://github.com/Tai-Wang/Depth-from-Motion)]
- **[DEVIANT]** DEVIANT: Depth EquiVarIAnt NeTwork for Monocular 3D Object Detection<br>
Abhinav Kumar, Garrick Brazil, Enrique Corona, Armin Parchami, Xiaoming Liu.<br>
In . [[2207.10758](https://arxiv.org/abs/2207.10758)] [[abhi1kumar/DEVIANT](https://github.com/abhi1kumar/DEVIANT)]
- **[DCD]** Densely Constrained Depth Estimator for Monocular 3D Object Detection<br>
Yingyan Li, Yuntao Chen, Jiawei He, Zhaoxiang Zhang.<br>
In ECCV 2022. [[2207.10047](https://arxiv.org/abs/2207.10047)] [[BraveGroup/DCD](https://github.com/BraveGroup/DCD)]
- **[AutoAlignV2]** AutoAlignV2: Deformable Feature Aggregation for Dynamic Multi-Modal 3D Object Detection.<br>
  Zehui Chen, Zhenyu Li, Shiquan Zhang, Liangji Fang, Qinhong Jiang, Feng Zhao.<br>
  In . [[2207.10316](https://arxiv.org/abs/2207.10316)] [[zehuichen123/AutoAlignV2](https://github.com/zehuichen123/AutoAlignV2)]
- **[ORA3D]** ORA3D: Overlap Region Aware Multi-view 3D Object Detection.<br>
  Wonseok Roh, Gyusam Chang, Seokha Moon, Giljoo Nam, Chanyoung Kim, Younghyun Kim, Sangpil Kim, Jinkyu Kim.<br>
  In . [[2207.00865](https://arxiv.org/abs/2207.00865)]
- **[PolarFormer]** PolarFormer: Multi-camera 3D Object Detection with Polar Transformers.<br>
  Yanqin Jiang, Li Zhang, Zhenwei Miao, Xiatian Zhu, Jin Gao, Weiming Hu, Yu-Gang Jiang.<br>
  In . [[2206.15398](https://arxiv.org/abs/2206.15398)]
- **[SRCN3D]** SRCN3D: Sparse R-CNN 3D Surround-View Camera Object Detection and Tracking for Autonomous Driving.<br>
  Yining Shi, Jingyan Shen, Yifan Sun, Yunlong Wang, Jiaxin Li, Shiqi Sun, Kun Jiang, Diange Yang.<br>
  In . [[2206.14451](https://arxiv.org/abs/2206.14451)] [[synsin0/SRCN3D](https://github.com/synsin0/SRCN3D)]
- **[PolarDETR]** Polar Parametrization for Vision-based Surround-View 3D Detection.<br>
  Shaoyu Chen, Xinggang Wang, Tianheng Cheng, Qian Zhang, Chang Huang, Wenyu Liu.<br>
  In . [[2206.10965](https://arxiv.org/abs/2206.10965)] [[hustvl/PolarDETR](https://github.com/hustvl/PolarDETR)]
- **[BEVDepth]** BEVDepth: Acquisition of Reliable Depth for Multi-view 3D Object Detection.<br>
  Yinhao Li, Zheng Ge, Guanyi Yu, Jinrong Yang, Zengran Wang, Yukang Shi, Jianjian Sun, Zeming Li.<br>
  In . [[2206.10092](https://arxiv.org/abs/2206.10092)] [[Megvii-BaseDetection/BEVDepth](https://github.com/Megvii-BaseDetection/BEVDepth)]
- **[Ego3RT]** Learning Ego 3D Representation as Ray Tracing.<br>
  Jiachen Lu, Zheyuan Zhou, Xiatian Zhu, Hang Xu, Li Zhang.<br>
  In . [[2206.04042](https://arxiv.org/abs/2206.04042)] [[fudan-zvg/Ego3RT](https://github.com/fudan-zvg/Ego3RT)]
- **[PETRv2]** PETRv2: A Unified Framework for 3D Perception from Multi-Camera Images.<br>
  Yingfei Liu, Junjie Yan, Fan Jia, Shuailin Li, Qi Gao, Tiancai Wang, Xiangyu Zhang, Jian Sun.<br>
  In . [[2206.01256](https://arxiv.org/abs/2206.01256)] [[megvii-research/PETR](https://github.com/megvii-research/PETR)]
- **[UVTR]** Unifying Voxel-based Representation with Transformer for 3D Object Detection<br>
  Yanwei Li, Yilun Chen, Xiaojuan Qi, Zeming Li, Jian Sun, Jiaya Jia.<br>
  In . [[2206.00630](https://arxiv.org/abs/2206.00630)] [[dvlab-research/UVTR](https://github.com/dvlab-research/UVTR)]
- **[BEVFusion2]** BEVFusion: A Simple and Robust LiDAR-Camera Fusion Framework<br>
  Tingting Liang, Hongwei Xie, Kaicheng Yu, Zhongyu Xia, Zhiwei Lin, Yongtao Wang, Tao Tang, Bing Wang, Zhi Tang.<br>
  In . [[2205.13790](https://arxiv.org/abs/2205.13790)] [[ADLab-AutoDrive/BEVFusion](https://github.com/ADLab-AutoDrive/BEVFusion)]
- **[BEVFusion1]** BEVFusion: Multi-Task Multi-Sensor Fusion with Unified Bird's-Eye View Representation<br>
  Zhijian Liu, Haotian Tang, Alexander Amini, Xinyu Yang, Huizi Mao, Daniela Rus, Song Han.<br>
  In . [[2205.13542](https://arxiv.org/abs/2205.13542)] [[mit-han-lab/bevfusion](https://github.com/mit-han-lab/bevfusion)]
- **[BEVerse]** BEVerse: Unified Perception and Prediction in Birds-Eye-View for Vision-Centric Autonomous Driving.<br>
  Yunpeng Zhang, Zheng Zhu, Wenzhao Zheng, Junjie Huang, Guan Huang, Jie Zhou, Jiwen Lu.<br>
  In . [[2205.09743](https://arxiv.org/abs/2205.09743)] [[zhangyp15/BEVerse](https://github.com/zhangyp15/BEVerse)]
- **[MUTR3D]** MUTR3D: A Multi-camera Tracking Framework via 3D-to-2D Queries.<br>
  Tianyuan Zhang, Xuanyao Chen, Yue Wang, Yilun Wang, Hang Zhao.<br>
  In CVPRW 2022. [[2205.00613](https://arxiv.org/abs/2205.00613)] [[a1600012888/MUTR3D](https://github.com/a1600012888/MUTR3D)]
- **[Graph-DETR3D]** Graph-DETR3D: Rethinking Overlapping Regions for Multi-View 3D Object Detection<br>
  Zehui Chen, Zhenyu Li, Shiquan Zhang, Liangji Fang, Qinhong Jiang, Feng Zhao.<br>
  In . [[2204.11582](https://arxiv.org/abs/2204.11582)]
- **[M2BEV]** M2BEV: Multi-Camera Joint 3D Detection and Segmentation with Unified Birds-Eye View Representation<br>
  Enze Xie, Zhiding Yu, Daquan Zhou, Jonah Philion, Anima Anandkumar, Sanja Fidler, Ping Luo, Jose M. Alvarez.<br>
  In . [[2204.05088](https://arxiv.org/abs/2204.05088)] [[NVlabs/M2BEV](https://github.com/NVlabs/M2BEV)]
- **[BEVFormer]** BEVFormer: Learning Bird's-Eye-View Representation from Multi-Camera Images via Spatiotemporal Transformers<br>
  Zhiqi Li, Wenhai Wang, Hongyang Li, Enze Xie, Chonghao Sima, Tong Lu, Qiao Yu, Jifeng Dai.<br>
  In . [[2203.17270](https://arxiv.org/abs/2203.17270)] [[zhiqi-li/BEVFormer](https://github.com/zhiqi-li/BEVFormer)]
- **[BEVDet4D]** BEVDet4D: Exploit Temporal Cues in Multi-camera 3D Object Detection.<br>
  Junjie Huang, Guan Huang.<br>
  In . [[2203.17054](https://arxiv.org/abs/2203.17054)] [[HuangJunJie2017/BEVDet](https://github.com/HuangJunJie2017/BEVDet)]
- **[PETR]** PETR: Position Embedding Transformation for Multi-View 3D Object Detection<br>
  Yingfei Liu, Tiancai Wang, Xiangyu Zhang, Jian Sun.<br>
  In . [[2203.05625](https://arxiv.org/abs/2203.05625)] [[megvii-research/PETR](https://github.com/megvii-research/PETR)]
- **[BEVDet]** BEVDet: High-performance Multi-camera 3D Object Detection in Bird-Eye-View.<br>
  Junjie Huang, Guan Huang, Zheng Zhu, Dalong Du.<br>
  In . [[2112.11790](https://arxiv.org/abs/2112.11790)] [[HuangJunJie2017/BEVDet](https://github.com/HuangJunJie2017/BEVDet)]
- **[DETR3D]** DETR3D: 3D Object Detection from Multi-view Images via 3D-to-2D Queries.<br>
  Yue Wang, Vitor Guizilini, Tianyuan Zhang, Yilun Wang, Hang Zhao, Justin Solomon.<br>
  In CoRL 2021. [[2110.06922](https://arxiv.org/abs/2110.06922)] [[wangyueft/detr3d](https://github.com/wangyueft/detr3d)]




### BEV Segmentation related
- **[UniFormer]** Unified Multi-view Fusion Transformer for Spatial-Temporal Representation in Bird's-Eye-View.<br>
Zequn Qin, Jingyu Chen, Chao Chen, Xiaozhi Chen, Xi Li.<br>
In . [[2207.08536](https://arxiv.org/abs/2207.08536)]
- **[CoBEVT]** CoBEVT: Cooperative Bird's Eye View Semantic Segmentation with Sparse Transformers.<br>
Runsheng Xu, Zhengzhong Tu, Hao Xiang, Wei Shao, Bolei Zhou, Jiaqi Ma.<br>
In . [[2207.02202](https://arxiv.org/abs/2207.02202)]
- **[Simple Baseline]** A Simple Baseline for BEV Perception Without LiDAR.<br>
Adam W. Harley, Zhaoyuan Fang, Jie Li, Rares Ambrus, Katerina Fragkiadaki.<br>
In . [[2206.07959](https://arxiv.org/abs/2206.07959)]
- **[GKT]** Efficient and Robust 2D-to-BEV Representation Learning via Geometry-guided Kernel Transformer<br>
Shaoyu Chen, Tianheng Cheng, Xinggang Wang, Wenming Meng, Qian Zhang, Wenyu Liu.<br>
In . [[2206.04584](https://arxiv.org/abs/2206.04584)] [[hustvl/GKT](https://github.com/hustvl/GKT)]
- **[ViT-BEVSeg]** ViT-BEVSeg: A Hierarchical Transformer Network for Monocular Birds-Eye-View Segmentation.<br>
Pramit Dutta, Ganesh Sistu, Senthil Yogamani, Edgar Galván, John McDonald.<br>
In WCCI 2022. [[2205.15667](https://arxiv.org/abs/2205.15667)]
- **[Cross-view Transformers]** Cross-view Transformers for real-time Map-view Semantic Segmentation.<br>
Brady Zhou, Philipp Krähenbühl.<br>
In CVPR 2022. [[2205.02833](https://arxiv.org/abs/2205.02833)] [[bradyz/cross_view_transformers](https://github.com/bradyz/cross_view_transformers)]
- **[GitNet]** GitNet: Geometric Prior-based Transformation for Birds-Eye-View Segmentation.<br>
Shi Gong, Xiaoqing Ye, Xiao Tan, Jingdong Wang, Errui Ding, Yu Zhou, Xiang Bai.<br>
In . [[2204.07733](https://arxiv.org/abs/2204.07733)]
- **[HFT]** HFT: Lifting Perspective Representations via Hybrid Feature Transformation.<br>
Jiayu Zou, Junrui Xiao, Zheng Zhu, Junjie Huang, Guan Huang, Dalong Du, Xingang Wang.<br>
In . [[2204.05068](https://arxiv.org/abs/2204.05068)] [[JiayuZou2020/HFT](https://github.com/JiayuZou2020/HFT)]
- **[PersFormer]** PersFormer: 3D Lane Detection via Perspective Transformer and the OpenLane Benchmark.<br>
Li Chen, Chonghao Sima, Yang Li, Zehan Zheng, Jiajie Xu, Xiangwei Geng, Hongyang Li, Conghui He, Jianping Shi, Yu Qiao, Junchi Yan.<br>
In . [[2203.11089](https://arxiv.org/abs/2203.11089)] [[OpenPerceptionX/PersFormer_3DLane](https://github.com/OpenPerceptionX/PersFormer_3DLane)]
- **[BEVSegFormer]** BEVSegFormer: Bird's Eye View Semantic Segmentation From Arbitrary Camera Rigs.<br>
Lang Peng, Zhirong Chen, Zhangjie Fu, Pengpeng Liang, Erkang Cheng.<br>
In . [[2203.04050](https://arxiv.org/abs/2203.04050)]
- **[STSU]** Structured Bird's-Eye-View Traffic Scene Understanding from Onboard Images.<br>
Yigit Baran Can, Alexander Liniger, Danda Pani Paudel, Luc Van Gool<br>
In ICCV 2021. [[2110.01997](https://arxiv.org/abs/2110.01997)] [[ybarancan/STSU](https://github.com/ybarancan/STSU)]
- **[TIM]** Translating Images into Maps.<br>
Avishkar Saha, Oscar Mendez Maldonado, Chris Russell, Richard Bowden<br>
In ICRA 2022. [[2110.00966](https://arxiv.org/abs/2110.00966)] [[avishkarsaha/translating-images-into-maps](https://github.com/avishkarsaha/translating-images-into-maps)]
- **[NEAT]** NEAT: Neural Attention Fields for End-to-End Autonomous Driving.<br>
Kashyap Chitta, Aditya Prakash, Andreas Geiger.<br>
In ICCV 2021. [[2109.04456](https://arxiv.org/abs/2109.04456)]
- **[BEV Panoptic]** Bird's-Eye-View Panoptic Segmentation Using Monocular Frontal View Images<br>
Nikhil Gosala, Abhinav Valada.<br>
In RA-L 2021. [[2108.03227](https://arxiv.org/abs/2108.03227)] [[code](http://rl.uni-freiburg.de/research/panoptic-bev)]
- **[Disentangling and Vectorization]** Disentangling and Vectorization: A 3D Visual Perception Approach for Autonomous Driving Based on Surround-View Fisheye Cameras.<br>
Zizhang Wu, Wenkai Zhang, Jizheng Wang, Man Wang, Yuanzhu Gan, Xinchao Gou, Muqing Fang, Jing Song.<br>
In IROS 2021. [[2107.08862](https://arxiv.org/abs/2107.08862)]
- **[HDMapNet]** HDMapNet: An Online HD Map Construction and Evaluation Framework<br>
Qi Li, Yue Wang, Yilun Wang, Hang Zhao.<br>
In ICRA 2022. [[2107.06307](https://arxiv.org/abs/2107.06307)] [[Tsinghua-MARS-Lab/HDMapNet](https://github.com/Tsinghua-MARS-Lab/HDMapNet)]
- **[FIERY]** FIERY: Future Instance Prediction in Bird's-Eye View from Surround Monocular Cameras<br>
Anthony Hu, Zak Murez, Nikhil Mohan, Sofia Dudas, Jeffrey Hawke, Vijay Badrinarayanan, Roberto Cipolla, Alex Kendall.<br>
In ICCV 2021. [[2104.10490](https://arxiv.org/abs/2104.10490)] [[wayveai/fiery](https://github.com/wayveai/fiery)]
- **[STA]** Enabling spatio-temporal aggregation in Birds-Eye-View Vehicle Estimation<br>
Avishkar Saha, Oscar Mendez, Chris Russell, Richard Bowden.
In ICRA 2021. [[paper](https://cvssp.org/Personal/OscarMendez/papers/pdf/SahaICRA2021.pdf)]
- **[EPOSH]** Bird’s Eye View Segmentation Using Lifted 2D Semantic Features.<br>
Isht Dwivedi, Srikanth Malla, Yi-Ting Chen, Behzad Dariush.<br>
In BMVC 2021. [[paper](https://www.bmvc2021-virtualconference.com/assets/papers/0772.pdf)]
- **[PYVA]** Projecting Your View Attentively: Monocular Road Scene Layout Estimation via Cross-view Transformation.<br>
Weixiang Yang, Qi Li, Wenxi Liu, Yuanlong Yu, Yuexin Ma, Shengfeng He, Jia Pan.<br>
In CVPR 2021. [[paper](https://openaccess.thecvf.com/content/CVPR2021/html/Yang_Projecting_Your_View_Attentively_Monocular_Road_Scene_Layout_Estimation_via_CVPR_2021_paper.html)] [[JonDoe-297/cross-view](https://github.com/JonDoe-297/cross-view)]
- **[BEV feat stitch]** Understanding Bird's-Eye View of Road Semantics using an Onboard Camera<br>
Yigit Baran Can, Alexander Liniger, Ozan Unal, Danda Paudel, Luc Van Gool.<br>
In RA-L 2021. [[2012.03040](https://arxiv.org/abs/2012.03040)] [[ybarancan/BEV_feat_stitch](https://github.com/ybarancan/BEV_feat_stitch)]
- **[LSS]** Lift, Splat, Shoot: Encoding Images From Arbitrary Camera Rigs by Implicitly Unprojecting to 3D.<br>
Jonah Philion, Sanja Fidler.<br>
In ECCV 2020. [[2008.05711](https://arxiv.org/abs/2008.05711)] [[nv-tlabs/lift-splat-shoot](https://github.com/nv-tlabs/lift-splat-shoot)]
- **[BEV-Seg]** BEV-Seg: Bird's Eye View Semantic Segmentation Using Geometry and Semantic Point Cloud<br>
Mong H. Ng, Kaahan Radia, Jianfei Chen, Dequan Wang, Ionel Gog, Joseph E. Gonzalez.<br>
In CVPRW 2020. [[2006.11436](https://arxiv.org/abs/2006.11436)]
- **[Cam2BEV]** A Sim2Real Deep Learning Approach for the Transformation of Images from Multiple Vehicle-Mounted Cameras to a Semantically Segmented Image in Bird's Eye View.<br>
Lennart Reiher, Bastian Lampe, Lutz Eckstein.<br>
In ITSC 2020. [[2005.04078](https://arxiv.org/abs/2005.04078)] [[ika-rwth-aachen/Cam2BEV](https://github.com/ika-rwth-aachen/Cam2BEV)]
- **[PyrOccNet]** Predicting Semantic Map Representations from Images using Pyramid Occupancy Networks<br>
Thomas Roddick, Roberto Cipolla.<br>
In . [[2003.13402](https://arxiv.org/abs/2003.13402)] [[tom-roddick/mono-semantic-maps](https://github.com/tom-roddick/mono-semantic-maps)]
- **[MonoLayout]** MonoLayout: Amodal scene layout from a single image<br>
Kaustubh Mani, Swapnil Daga, Shubhika Garg, N. Sai Shankar, Krishna Murthy Jatavallabhula, K. Madhava Krishna.<br>
In WACV 2020. [[2002.08394](https://arxiv.org/abs/2002.08394)] [[hbutsuak95/monolayout](https://github.com/hbutsuak95/monolayout)]
- **[VPN]** Cross-view Semantic Segmentation for Sensing Surroundings<br>
Bowen Pan, Jiankai Sun, Ho Yin Tiga Leung, Alex Andonian, Bolei Zhou.<br>
In RA-L 2020. [[1906.03560](https://arxiv.org/abs/1906.03560)] [[pbw-Berwin/View-Parsing-Network](https://github.com/pbw-Berwin/View-Parsing-Network)]
- **[OFT]** Orthographic Feature Transform for Monocular 3D Object Detection<br>
Thomas Roddick, Alex Kendall, Roberto Cipolla.<br>
In BMVC 2019. [[1811.08188](https://arxiv.org/abs/1811.08188)] [[tom-roddick/oft](https://github.com/tom-roddick/oft)]
- **[VED]** Monocular Semantic Occupancy Grid Mapping with Convolutional Variational Encoder-Decoder Networks.<br>
Chenyang Lu, Marinus Jacobus Gerardus van de Molengraft, Gijs Dubbelman.<br>
In RA-L 2019. [[1804.02176](https://arxiv.org/abs/1804.02176)]
- Learning to Look around Objects for Top-View Representations of Outdoor Scenes<br>
Samuel Schulter, Menghua Zhai, Nathan Jacobs, Manmohan Chandraker.<br>
In ECCV 2018. [[1803.10870](https://arxiv.org/abs/1803.10870)]
- **[MapNet]** MapNet: An Allocentric Spatial Memory for Mapping Environments.<br>
Joao F. Henriques Andrea Vedaldi.<br>
In CVPR 2018. [[paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Henriques_MapNet_An_Allocentric_CVPR_2018_paper.pdf)]
- **[Mapping]** Automatic Dense Visual Semantic Mapping from Street-Level Imagery.<br>
Sunando Sengupta, Paul Sturgess, L’ubor Ladický, Philip H. S. Torr.<br>
In IROS 2012. [[paper](https://www.robots.ox.ac.uk/~tvg/publications/2012/IROS_Mapping_ss.pdf)]


### LiDAR
- **[Backbone]** PointPillars Backbone Type Selection For Fast and Accurate LiDAR Object Detection<br>
Konrad Lis, Tomasz Kryjak.<br>
In ICCVG 2022. [[2209.15252](https://arxiv.org/abs/2209.15252)]
- **[SPSConv]** Spatial Pruned Sparse Convolution for Efficient 3D Object Detection<br>
Jianhui Liu, Yukang Chen, Xiaoqing Ye, Zhuotao Tian, Xiao Tan, Xiaojuan Qi.<br>
In NeurIPS 2022. [[2209.14201](https://arxiv.org/abs/2209.14201)]
- **[MDRNet]** Rethinking Dimensionality Reduction in Grid-based 3D Object Detection.<br>
Dihe Huang, Ying Chen, Yikang Ding, Jinli Liao, Jianlin Liu, Kai Wu, Qiang Nie, Yong Liu, Chengjie Wang.<br>
In . [[2209.09464](https://arxiv.org/abs/2209.09464)]
- **[LidarMultiNet]** LidarMultiNet: Towards a Unified Multi-task Network for LiDAR Perception.<br>
Dongqiangzi Ye, Zixiang Zhou, Weijia Chen, Yufei Xie, Yu Wang, Panqu Wang, Hassan Foroosh.<br>
In . [[2209.09385](https://arxiv.org/abs/2209.09385)]
- **[CenterFormer]** CenterFormer: Center-based Transformer for 3D Object Detection.<br>
Zixiang Zhou, Xiangchen Zhao, Yu Wang, Panqu Wang, Hassan Foroosh.<br>
In ECCV 2022. [[2209.05588](https://arxiv.org/abs/2209.05588)] [[TuSimple/centerformer](https://github.com/TuSimple/centerformer)]
- **[Graph R-CNN]** Graph R-CNN: Towards Accurate 3D Object Detection with Semantic-Decorated Local Graph.<br>
Honghui Yang, Zili Liu, Xiaopei Wu, Wenxiao Wang, Wei Qian, Xiaofei He, Deng Cai.<br>
In ECCV 2022. [[2208.03624](https://arxiv.org/abs/2208.03624)] [[Nightmare-n/GraphRCNN](https://github.com/Nightmare-n/GraphRCNN)]
- **[LG3D]** Label-Guided Auxiliary Training Improves 3D Object Detector.<br>
Yaomin Huang, Xinmei Liu, Yichen Zhu, Zhiyuan Xu, Chaomin Shen, Zhengping Che, Guixu Zhang, Yaxin Peng, Feifei Feng, Jian Tang.<br>
In ECCV 2022. [[2207.11753](https://arxiv.org/abs/2207.11753)]
- **[DeMF]** Boosting 3D Object Detection via Object-Focused Image Fusion.<br>
Hao Yang, Chen Shi, Yihong Chen, Liwei Wang.<br>
In . [[2207.10589](https://arxiv.org/abs/2207.10589)] [[haoy945/DeMF](https://github.com/haoy945/DeMF)]
- **[FSD]** Fully Sparse 3D Object Detection.<br>
Lue Fan, Feng Wang, Naiyan Wang, Zhaoxiang Zhang.<br>
In . [[2207.10035](https://arxiv.org/abs/2207.10035)] [[TuSimple/SST](https://github.com/TuSimple/SST)]
- **[RDIoU]** Rethinking IoU-based Optimization for Single-stage 3D Object Detection.<br>
Hualian Sheng, Sijia Cai, Na Zhao, Bing Deng, Jianqiang Huang, Xian-Sheng Hua, Min-Jian Zhao, Gim Hee Lee.<br>
In . [[2207.09332](https://arxiv.org/abs/2207.09332)] [[hlsheng1/RDIoU](https://github.com/hlsheng1/RDIoU)]
- **[LargeKernel3D]** Scaling up Kernels in 3D CNNs.<br>
Yukang Chen, Jianhui Liu, Xiaojuan Qi, Xiangyu Zhang, Jian Sun, Jiaya Jia.<br>
IN . [[2206.10555](https://arxiv.org/abs/2206.10555)] [[dvlab-research/LargeKernel3D](https://github.com/dvlab-research/LargeKernel3D)]
- **[Occam Laser]** OccAM’s Laser: Occlusion-based Attribution Maps for 3D Object Detectors on LiDAR Data.<br>
David Schinagl, Georg Krispel, Horst Possegger, Peter M. Roth, Horst Bischof.<br>
In CVPR 2022. [[paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Schinagl_OccAMs_Laser_Occlusion-Based_Attribution_Maps_for_3D_Object_Detectors_on_CVPR_2022_paper.pdf)] [[dschinagl/occam](https://github.com/dschinagl/occam)]
- **[PillarNet]** PillarNet: Real-Time and High-Performance Pillar-based 3D Object Detection.<br>
Guangsheng Shi, Ruifeng Li, Chao Ma.<br>
In . [[2205.07403](https://arxiv.org/abs/2205.07403)] [[agent-sgs/PillarNet](https://github.com/agent-sgs/PillarNet)]
- **[MPPNet]** MPPNet: Multi-Frame Feature Intertwining with Proxy Points for 3D Temporal Object Detection.<br>
Xuesong Chen, Shaoshuai Shi, Benjin Zhu, Ka Chun Cheung, Hang Xu, Hongsheng Li.<br>
In . [[2205.05979](https://arxiv.org/abs/2205.05979)] [[open-mmlab/OpenPCDet](https://github.com/open-mmlab/OpenPCDet)]
- **[FocalsConv]** Focal Sparse Convolutional Networks for 3D Object Detection.<br>
Yukang Chen, Yanwei Li, Xiangyu Zhang, Jian Sun, Jiaya Jia.<br>
In CVPR 2022. [[2204.12463](https://arxiv.org/abs/2204.12463)] [[dvlab-research/FocalsConv](https://github.com/dvlab-research/FocalsConv)]
- **[MODEST]** Learning to Detect Mobile Objects from LiDAR Scans Without Labels.<br>
Yurong You, Katie Z Luo, Cheng Perng Phoo, Wei-Lun Chao, Wen Sun, Bharath Hariharan, Mark Campbell, Kilian Q. Weinberger.<br>
In CVPR 2022. [[2203.15882](https://arxiv.org/abs/2203.15882)] [[YurongYou/MODEST](https://github.com/YurongYou/MODEST)]
- **[AziNorm]** AziNorm: Exploiting the Radial Symmetry of Point Cloud for Azimuth-Normalized 3D Perception.<br>
Shaoyu Chen, Xinggang Wang, Tianheng Cheng, Wenqiang Zhang, Qian Zhang, Chang Huang, Wenyu Liu.<br>
In CVPR 2022. [[2203.13090](https://arxiv.org/abs/2203.13090)] [[hustvl/AziNorm](https://github.com/hustvl/AziNorm)]
- **[IA-SSD]** Not All Points Are Equal: Learning Highly Efficient Point-based Detectors for 3D LiDAR Point Clouds.<br>
Yifan Zhang, Qingyong Hu, Guoquan Xu, Yanxin Ma, Jianwei Wan, Yulan Guo.<br>
In CVPR 2022. [[2203.11139](https://arxiv.org/abs/2203.11139)] [[yifanzhang713/IA-SSD](https://github.com/yifanzhang713/IA-SSD)]
- **[PDV]** Point Density-Aware Voxels for LiDAR 3D Object Detection<br>
Jordan S. K. Hu, Tianshu Kuai, Steven L. Waslander.<br>
In CVPR 2022. [[2203.05662](https://arxiv.org/abs/2203.05662)] [[TRAILab/PDV](https://github.com/TRAILab/PDV)]
- **[PiFeNet]** Accurate and Real-time 3D Pedestrian Detection Using an Efficient Attentive Pillar Network<br>
Duy-Tho Le, Hengcan Shi, Hamid Rezatofighi, Jianfei Cai.<br>
In . [[2112.15458](https://arxiv.org/abs/2112.15458)] [[ldtho/PiFeNet](https://github.com/ldtho/PiFeNet)]
- **[SST]** Embracing Single Stride 3D Object Detector with Sparse Transformer.<br>
Lue Fan, Ziqi Pang, Tianyuan Zhang, Yu-Xiong Wang, Hang Zhao, Feng Wang, Naiyan Wang, Zhaoxiang Zhang.<br>
In . [[2112.06375](https://arxiv.org/abs/2112.06375)] [[TuSimple/SST](https://github.com/TuSimple/SST)]
- **[Pyramid R-CNN]** Pyramid R-CNN: Towards Better Performance and Adaptability for 3D Object Detection.<br>
Jiageng Mao, Minzhe Niu, Haoyue Bai, Xiaodan Liang, Hang Xu, Chunjing Xu.<br>
In ICCV 2021. [[2109.02499](https://arxiv.org/abs/2109.02499)]
- **[Object DGCNN]** Object DGCNN: 3D Object Detection using Dynamic Graphs.<br>
Yue Wang, Justin Solomon.<br>
In NeurIPS 2021. [[2110.06923](https://arxiv.org/abs/2110.06923)] [[wangyueft/detr3d](https://github.com/wangyueft/detr3d)]
- **[3DETR]** An End-to-End Transformer Model for 3D Object Detection.<br>
Ishan Misra, Rohit Girdhar, Armand Joulin.<br>
In ICCV 2021. [[2109.08141](https://arxiv.org/abs/2109.08141)] [[facebookresearch/3detr](https://github.com/facebookresearch/3detr)]
- **[VoTr]** Voxel Transformer for 3D Object Detection.<br>
Jiageng Mao, Yujing Xue, Minzhe Niu, Haoyue Bai, Jiashi Feng, Xiaodan Liang, Hang Xu, Chunjing Xu.<br>
In ICCV 2021. [[2109.02497](https://arxiv.org/abs/2109.02497)]
- **[RangeIoUDet]** RangeIoUDet: Range Image based Real-Time 3D Object Detector<br>
Optimized by Intersection over Union.<br>
Zhidong Liang, Zehan Zhang, Ming Zhang, Xian Zhao, Shiliang Pu.
In CVPR 2021. [[paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Liang_RangeIoUDet_Range_Image_Based_Real-Time_3D_Object_Detector_Optimized_by_CVPR_2021_paper.pdf)]
- **[RSN]** RSN: Range Sparse Net for Efficient, Accurate LiDAR 3D Object Detection<br>
Pei Sun, Weiyue Wang, Yuning Chai, Gamaleldin Elsayed, Alex Bewley, Xiao Zhang, Cristian Sminchisescu, Dragomir Anguelov.<br>
In . [[2106.13365](https://arxiv.org/abs/2106.13365)]
- **[M3DeTR]** M3DeTR: Multi-representation, Multi-scale, Mutual-relation 3D Object Detection with Transformers.<br>
Tianrui Guan, Jun Wang, Shiyi Lan, Rohan Chandra, Zuxuan Wu, Larry Davis, Dinesh Manocha.<br>
In WACV 2022. [[2104.11896](https://arxiv.org/abs/2104.11896)] [[rayguan97/M3DETR](https://github.com/rayguan97/M3DETR)]
- **[SE-SSD]** SE-SSD: Self-Ensembling Single-Stage Object Detector From Point Cloud.<br>
Wu Zheng, Weiliang Tang, Li Jiang, Chi-Wing Fu.<br>
In CVPR 2021. [[2104.09804](https://arxiv.org/abs/2104.09804)] [[Vegeta2020/SE-SSD](https://github.com/Vegeta2020/SE-SSD)]
- **[LiDAR RCNN]** LiDAR R-CNN: An Efficient and Universal 3D Object Detector<br>
Zhichao Li, Feng Wang, Naiyan Wang.<br>
In CVPR 2021. [[2103.15297](https://arxiv.org/abs/2103.15297)] [[tusen-ai/LiDAR_RCNN](https://github.com/tusen-ai/LiDAR_RCNN)]
- **[PV-RCNN++]** PV-RCNN++: Point-Voxel Feature Set Abstraction With Local Vector Representation for 3D Object Detection.<br>
Shaoshuai Shi, Li Jiang, Jiajun Deng, Zhe Wang, Chaoxu Guo, Jianping Shi, Xiaogang Wang, Hongsheng Li.<br>
In . [[2102.00463](https://arxiv.org/abs/2102.00463)] [[open-mmlab/OpenPCDet](https://github.com/open-mmlab/OpenPCDet)]
- **[Voxel R-CNN]** Voxel R-CNN: Towards High Performance Voxel-based 3D Object Detection.<br>
Jiajun Deng, Shaoshuai Shi, Peiwei Li, Wengang Zhou, Yanyong Zhang, Houqiang Li.<br>
In AAAI 2021. [[2012.15712](https://arxiv.org/abs/2012.15712)] [[djiajunustc/Voxel-R-CNN](https://github.com/djiajunustc/Voxel-R-CNN)]
- **[Pointformer]** 3D Object Detection with Pointformer.<br>
Xuran Pan, Zhuofan Xia, Shiji Song, Li Erran Li, Gao Huang.<br>
In CVPR 2020. [[2012.11409](https://arxiv.org/abs/2012.11409)] [[Vladimir2506/Pointformer](https://github.com/Vladimir2506/Pointformer)]
- **[Deformable PV-RCNN]** Deformable PV-RCNN: Improving 3D Object Detection with Learned Deformations.<br>
Prarthana Bhattacharyya, Krzysztof Czarnecki.<br>
In ECCVW 2020. [[2008.08766](https://arxiv.org/abs/2008.08766)]
- **[CenterNet3D]** CenterNet3D: An Anchor Free Object Detector for Point Cloud.<br>
Guojun Wang, Jian Wu, Bin Tian, Siyu Teng, Long Chen, Dongpu Cao.<br>
In IEEE Transactions on Intelligent Transportation Systems 2021. [[2007.07214](https://arxiv.org/abs/2007.07214)] [[wangguojun2018/CenterNet3d](https://github.com/wangguojun2018/CenterNet3d)]
- **[CenterPoint]** Center-based 3D Object Detection and Tracking.<br>
Tianwei Yin, Xingyi Zhou, Philipp Krähenbühl.<br>
In CVPR 2021. [[2006.11275](https://arxiv.org/abs/2006.11275)] [[tianweiy/CenterPoint](https://github.com/tianweiy/CenterPoint)]
- **[SASSD]** Structure Aware Single-stage 3D Object Detection from Point Cloud.<br>
Chenhang He, Hui Zeng, Jianqiang Huang, Xian-Sheng Hua, Lei Zhang.<br>
In CVPR 2020. [[paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/He_Structure_Aware_Single-Stage_3D_Object_Detection_From_Point_Cloud_CVPR_2020_paper.pdf)] [[skyhehe123/SA-SSD](https://github.com/skyhehe123/SA-SSD)]
- **[PV-RCNN]** PV-RCNN: Point-Voxel Feature Set Abstraction for 3D Object Detection.<br>
Shaoshuai Shi, Chaoxu Guo, Li Jiang, Zhe Wang, Jianping Shi, Xiaogang Wang, Hongsheng Li.<br>
In CVPR 2020. [[1912.13192](https://arxiv.org/abs/1912.13192)] [[open-mmlab/OpenPCDet](https://github.com/open-mmlab/OpenPCDet)]
- **[HotSpotNet]** Object as Hotspots: An Anchor-Free 3D Object Detection Approach via Firing of Hotspots.<br>
Qi Chen, Lin Sun, Zhixin Wang, Kui Jia, Alan Yuille.<br>
In . [[1912.12791](https://arxiv.org/abs/1912.12791)]
- **[MVF]** End-to-End Multi-View Fusion for 3D Object Detection in LiDAR Point Clouds.<br>
Yin Zhou, Pei Sun, Yu Zhang, Dragomir Anguelov, Jiyang Gao, Tom Ouyang, James Guo, Jiquan Ngiam, Vijay Vasudevan.<br>
In CoRL 2019. [[1910.06528](https://arxiv.org/abs/1910.06528)]
- **[CBGS]** Class-balanced Grouping and Sampling for Point Cloud 3D Object Detection.<br>
Benjin Zhu, Zhengkai Jiang, Xiangxin Zhou, Zeming Li, Gang Yu.<br>
In . [[1908.09492](https://arxiv.org/abs/1908.09492)]
- **[VoteNet]** Deep Hough Voting for 3D Object Detection in Point Clouds.<br>
Charles R. Qi, Or Litany, Kaiming He, Leonidas J. Guibas.<br>
In ICCV 2019. [[1904.09664](https://arxiv.org/abs/1904.09664)] [[facebookresearch/votenet](https://github.com/facebookresearch/votenet)]
- **[Frustum ConvNet]** Frustum ConvNet: Sliding Frustums to Aggregate Local Point-Wise Features for Amodal 3D Object Detection.<br>
Zhixin Wang, Kui Jia.<br>
In IROS 2019. [[1903.01864](https://arxiv.org/abs/1903.01864)] [[zhixinwang/frustum-convnet](https://github.com/zhixinwang/frustum-convnet)]
- **[PIXOR]** PIXOR: Real-time 3D Object Detection from Point Clouds.<br>
Bin Yang, Wenjie Luo, Raquel Urtasun.<br>
In CVPR 2018. [[1902.06326](https://arxiv.org/abs/1902.06326)]
- **[PointPillars]** PointPillars: Fast Encoders for Object Detection from Point Clouds.<br>
Alex H. Lang, Sourabh Vora, Holger Caesar, Lubing Zhou, Jiong Yang, Oscar Beijbom.<br>
In CVPR 2019. [[1812.05784](https://arxiv.org/abs/1812.05784)]
- **[PointRCNN]** PointRCNN: 3D Object Proposal Generation and Detection from Point Cloud.<br>
Shaoshuai Shi, Xiaogang Wang, Hongsheng Li.<br>
In CVPR 2019. [[1812.04244](https://arxiv.org/abs/1812.04244)] [[sshaoshuai/PointRCNN](https://github.com/sshaoshuai/PointRCNN)]
- **[BirdNet]** BirdNet: a 3D Object Detection Framework from LiDAR information.<br>
Jorge Beltran, Carlos Guindel, Francisco Miguel Moreno, Daniel Cruzado, Fernando Garcia, Arturo de la Escalera.<br>
In ITSC 2018. [[1805.01195](https://arxiv.org/abs/1805.01195)]
- **[SECOND]** SECOND: Sparsely Embedded Convolutional Detection.<br>
Yan Yan, Yuxing Mao, Bo Li.<br>
In Sensors 2018. [[paper](https://www.mdpi.com/1424-8220/18/10/3337)]
- **[Frustum PointNet]** Frustum PointNets for 3D Object Detection from RGB-D Data.<br>
Charles R. Qi, Wei Liu, Chenxia Wu, Hao Su, Leonidas J. Guibas.<br>
In . [[1711.08488](https://arxiv.org/abs/1711.08488)]
- **[VoxelNet]** VoxelNet: End-to-End Learning for Point Cloud Based 3D Object Detection.<br>
Yin Zhou, Oncel Tuzel.<br>
In . [[1711.06396](https://arxiv.org/abs/1711.06396)]
- **[PointNet++]** PointNet++: Deep Hierarchical Feature Learning on Point Sets in a Metric Space.<br>
Charles R. Qi, Li Yi, Hao Su, Leonidas J. Guibas.<br>
In NIPS 2017 . [[1706.02413](https://arxiv.org/abs/1706.02413)] [[charlesq34/pointnet2](https://github.com/charlesq34/pointnet2)]
- **[PointNet]** PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation<br>
Charles R. Qi, Hao Su, Kaichun Mo, Leonidas J. Guibas.<br>
In CVPR 2017. [[1612.00593](https://arxiv.org/abs/1612.00593)] [[charlesq34/pointnet](https://github.com/charlesq34/pointnet)]
- 3D Fully Convolutional Network for Vehicle Detection in Point Cloud.
Bo Li.
In . [[1611.08069](https://arxiv.org/abs/1611.08069)]
- **[VeloFCN]** Vehicle Detection from 3D Lidar Using Fully Convolutional Network.<br>
Bo Li, Tianlei Zhang, Tian Xia.<br>
In Robotics: Science and Systems, 2016. [[1608.07916](https://arxiv.org/abs/1608.07916)]


### DETR Series
- **[Group DETR v2]** Group DETR v2: Strong Object Detector with Encoder-Decoder Pretraining.<br>
Qiang Chen, Jian Wang, Chuchu Han, Shan Zhang, Zexian Li, Xiaokang Chen, Jiahui Chen, Xiaodi Wang, Shuming Han, Gang Zhang, Haocheng Feng, Kun Yao, Junyu Han, Errui Ding, Jingdong Wang.<br>
In . [[2211.03594](https://arxiv.org/abs/2211.03594)]
- **[IMFA-DETR]** Towards Efficient Use of Multi-Scale Features in Transformer-Based Object Detectors<br>
Gongjie Zhang, Zhipeng Luo, Yingchen Yu, Zichen Tian, Jingyi Zhang, Shijian Lu.<br>
In . [[2208.11356](https://arxiv.org/abs/2208.11356)] [[ZhangGongjie/IMFA](https://github.com/ZhangGongjie/IMFA)]
- **[Group DETR]** Group DETR: Fast DETR Training with Group-Wise One-to-Many Assignment.<br>
Qiang Chen, Xiaokang Chen, Jian Wang, Haocheng Feng, Junyu Han, Errui Ding, Gang Zeng, Jingdong Wang.<br>
In . [[2207.13085](https://arxiv.org/abs/2207.13085)]
- **[H-DETR]** DETRs with Hybrid Matching.<br>
Ding Jia, Yuhui Yuan, Haodi He, Xiaopei Wu, Haojun Yu, Weihong Lin, Lei Sun, Chao Zhang, Han Hu.<br>
In . [[2207.13080](https://arxiv.org/abs/2207.13080)] [[HDETR/H-Deformable-DETR](https://github.com/HDETR/H-Deformable-DETR)]
- **[DETR++]** DETR++: Taming Your Multi-Scale Detection Transformer.<br>
Chi Zhang, Lijuan Liu, Xiaoxue Zang, Frederick Liu, Hao Zhang, Xinying Song, Jindong Chen.<br>
In CVPRW 2022. [[2206.02977](https://arxiv.org/abs/2206.02977)]
- **[Mask DINO]** Mask DINO: Towards A Unified Transformer-based Framework for Object Detection and Segmentation.<br>
Feng Li, Hao Zhang, Huaizhe xu, Shilong Liu, Lei Zhang, Lionel M. Ni, Heung-Yeung Shum.<br>
In . [[2206.02777](https://arxiv.org/abs/2206.02777)] [[IDEACVR/MaskDINO](https://github.com/IDEACVR/MaskDINO)]
- **[DDQ]** What Are Expected Queries in End-to-End Object Detection?<br>
Shilong Zhang, Xinjiang Wang, Jiaqi Wang, Jiangmiao Pang, Kai Chen.<br>
In . [[2206.01232](https://arxiv.org/abs/2206.01232)] [[jshilong/DDQ](https://github.com/jshilong/DDQ)]
- **[Dynamic Sparse R-CNN]** Dynamic Sparse R-CNN.<br>
Qinghang Hong, Fengming Liu, Dong Li, Ji Liu, Lu Tian, Yi Shan.<br>
In CVPR 2022. [[2205.02101](https://arxiv.org/abs/2205.02101)]
- **[DINO]** DINO: DETR with Improved DeNoising Anchor Boxes for End-to-End Object Detection<br>
Hao Zhang, Feng Li, Shilong Liu, Lei Zhang, Hang Su, Jun Zhu, Lionel M. Ni, Heung-Yeung Shum.<br>
In . [[2203.03605](https://arxiv.org/abs/2203.03605)]
- **[DN-DETR]** DN-DETR: Accelerate DETR Training by Introducing Query DeNoising.<br>
Feng Li, Hao Zhang, Shilong Liu, Jian Guo, Lionel M. Ni, Lei Zhang.<br>
In CVPR 2022. [[2203.01305](https://arxiv.org/abs/2203.01305)] [[IDEA-opensource/DN-DETR](https://github.com/IDEA-opensource/DN-DETR)]
- **[D^2ETR]** D^2ETR: Decoder-Only DETR with Computationally Efficient Cross-Scale Attention.<br>
Junyu Lin, Xiaofeng Mao, Yuefeng Chen, Lei Xu, Yuan He, Hui Xue.<br>
In . [[2203.00860](https://arxiv.org/abs/2203.00860)]
- **[DAB-DETR]** DAB-DETR: Dynamic Anchor Boxes are Better Queries for DETR.<br>
Shilong Liu, Feng Li, Hao Zhang, Xiao Yang, Xianbiao Qi, Hang Su, Jun Zhu, Lei Zhang.<br>
In ICLR 2022. [[2201.12329](https://arxiv.org/abs/2201.12329)] [[IDEA-opensource/DAB-DETR](https://github.com/IDEA-opensource/DAB-DETR)]
- **[Deformable Attention]** Vision Transformer with Deformable Attention.<br>
Zhuofan Xia, Xuran Pan, Shiji Song, Li Erran Li, Gao Huang.<br>
In CVPR 2022. [[2201.00520](https://arxiv.org/abs/2201.00520)] [[LeapLabTHU/DAT](https://github.com/LeapLabTHU/DAT)]
- **[Sparse DETR]** Sparse DETR: Efficient End-to-End Object Detection with Learnable Sparsity<br>
Byungseok Roh, JaeWoong Shin, Wuhyun Shin, Saehoon Kim.<br>
In ICLR 2022. [[2111.14330](https://arxiv.org/abs/2111.14330)] [[kakaobrain/sparse-detr](https://github.com/kakaobrain/sparse-detr)]
- **[Anchor DETR]** Anchor DETR: Query Design for Transformer-Based Object Detection.<br>
Yingming Wang, Xiangyu Zhang, Tong Yang, Jian Sun.<br>
In AAAI 2022. [[2109.07107](https://arxiv.org/abs/2109.07107)] [[megvii-research/AnchorDETR](https://github.com/megvii-research/AnchorDETR)]
- **[Dynamic DETR]** Dynamic DETR: End-to-End Object Detection With Dynamic Attention.<br>
Xiyang Dai, Yinpeng Chen, Jianwei Yang, Pengchuan Zhang, Lu Yuan, Lei Zhang.<br>
In ICCV 2021. [[paper](https://openaccess.thecvf.com/content/ICCV2021/html/Dai_Dynamic_DETR_End-to-End_Object_Detection_With_Dynamic_Attention_ICCV_2021_paper.html?ref=https://githubhelp.com)]
- **[Conditional DETR]** Conditional DETR for Fast Training Convergence<br>
Depu Meng, Xiaokang Chen, Zejia Fan, Gang Zeng, Houqiang Li, Yuhui Yuan, Lei Sun, Jingdong Wang.<br>
In ICCV 2021. [[2108.06152](https://arxiv.org/abs/2108.06152)] [[Atten4Vis/ConditionalDETR](https://github.com/Atten4Vis/ConditionalDETR)]
- **[Efficient DETR]** Efficient DETR: Improving End-to-End Object Detector with Dense Prior<br>
Zhuyu Yao, Jiangbo Ai, Boxun Li, Chi Zhang.<br>
In . [[2104.01318](https://arxiv.org/abs/2104.01318)]
- **[SMCA]** Fast Convergence of DETR with Spatially Modulated Co-Attention<br>
Peng Gao, Minghang Zheng, Xiaogang Wang, Jifeng Dai, Hongsheng Li.<br>
In . [[2101.07448](https://arxiv.org/abs/2101.07448)] [[gaopengcuhk/SMCA-DETR](https://github.com/gaopengcuhk/SMCA-DETR)]
- **[Sparse R-CNN]** Sparse R-CNN: End-to-End Object Detection with Learnable Proposals<br>
Peize Sun, Rufeng Zhang, Yi Jiang, Tao Kong, Chenfeng Xu, Wei Zhan, Masayoshi Tomizuka, Lei Li, Zehuan Yuan, Changhu Wang, Ping Luo.<br>
In . [[2011.12450](https://arxiv.org/abs/2011.12450)] [[PeizeSun/SparseR-CNN](https://github.com/PeizeSun/SparseR-CNN)]
- **[TSP]** Rethinking Transformer-based Set Prediction for Object Detection<br>
Zhiqing Sun, Shengcao Cao, Yiming Yang, Kris Kitani.<br>
In ICCV 2021. [[2011.10881](https://arxiv.org/abs/2011.10881)]
- **[Deformable DETR]** Deformable DETR: Deformable Transformers for End-to-End Object Detection.<br>
Xizhou Zhu, Weijie Su, Lewei Lu, Bin Li, Xiaogang Wang, Jifeng Dai.<br>
In ICLR 2021. [[2010.04159](https://arxiv.org/abs/2010.04159)] [[fundamentalvision/Deformable-DETR](https://github.com/fundamentalvision/Deformable-DETR)]
- **[DETR]** End-to-End Object Detection with Transformers.<br>
Nicolas Carion, Francisco Massa, Gabriel Synnaeve, Nicolas Usunier, Alexander Kirillov, Sergey Zagoruyko.<br>
In [[2005.12872](https://arxiv.org/abs/2005.12872)] [[facebookresearch/detr](https://github.com/facebookresearch/detr)]





