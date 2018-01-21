# Tracking-paper-list
From: https://zhuanlan.zhihu.com/p/27292838

写文章
目标跟踪相关资源（含模型，CVPR2017论文，代码，牛人等）持续更新
极视角
极视角
1
7 个月前

Update:2017/11/1

新增CSR-DCF [code]部分。


本文转自 @Qiang Wang 的foolwood/benchmark_results。
Visual Trackers

    CREST: Yibing Song, Chao Ma, Lijun Gong, Jiawei Zhang, Rynson Lau, Ming-Hsuan Yang. "CREST: Convolutional Residual Learning for Visual Tracking." ICCV (2017 Spotlight). [paper] [project] [github]
    EAST: Chen Huang, Simon Lucey, Deva Ramanan. "Learning Policies for Adaptive Tracking with Deep Feature Cascades." ICCV (2017 Spotlight). [paper] [supp]
    PTAV: Heng Fan and Haibin Ling. "Parallel Tracking and Verifying: A Framework for Real-Time and High Accuracy Visual Tracking." ICCV (2017). [paper] [supp] [project] [code]
    BACF: Hamed Kiani Galoogahi, Ashton Fagg, Simon Lucey. "Learning Background-Aware Correlation Filters for Visual Tracking." ICCV (2017). [paper] [supp]
    TSN: Zhu Teng, Junliang Xing, Qiang Wang, Congyan Lang, Songhe Feng and Yi Jin. "Robust Object Tracking based on Temporal and Spatial Deep Networks." ICCV (2017). [paper]
    p-tracker: James Supančič, III; Deva Ramanan. "Tracking as Online Decision-Making: Learning a Policy From Streaming Videos With Reinforcement Learning." ICCV (2017). [paper] [supp]
    DSiam: Qing Guo; Wei Feng; Ce Zhou; Rui Huang; Liang Wan; Song Wang. "Learning Dynamic Siamese Network for Visual Object Tracking." ICCV (2017). [paper]
    SP-KCF: Xin Sun; Ngai-Man Cheung; Hongxun Yao; Yiluan Guo. "Non-Rigid Object Tracking via Deformable Patches Using Shape-Preserved KCF and Level Sets." ICCV (2017). [paper]
    UCT: Zheng Zhu, Guan Huang, Wei Zou, Dalong Du, Chang Huang. "UCT: Learning Unified Convolutional Networks for Real-Time Visual Tracking." ICCV workshop (2017). [paper]
    Tobias Bottger, Patrick Follmann. "The Benefits of Evaluating Tracker Performance Using Pixel-Wise Segmentations." ICCV workshop (2017). [paper]
    CFWCR: Zhiqun He, Yingruo Fan, Junfei Zhuang, Yuan Dong, HongLiang Bai. "Correlation Filters With Weighted Convolution Responses." ICCV workshop (2017). [paper]
    IBCCF: Feng Li, Yingjie Yao, Peihua Li, David Zhang, Wangmeng Zuo, Ming-Hsuan Yang. "Integrating Boundary and Center Correlation Filters for Visual Tracking With Aspect Ratio Variation." ICCV workshop (2017). [paper]
    RFL: Tianyu Yang, Antoni B. Chan. "Recurrent Filter Learning for Visual Tracking." ICCV workshop (2017). [paper]
    ECO: Martin Danelljan, Goutam Bhat, Fahad Shahbaz Khan, Michael Felsberg. "ECO: Efficient Convolution Operators for Tracking." CVPR (2017). [paper] [project] [github]
    CFNet: Jack Valmadre, Luca Bertinetto, João F. Henriques, Andrea Vedaldi, Philip H. S. Torr. "End-to-end representation learning for Correlation Filter based tracking." CVPR (2017). [paper] [project] [github]
    CACF: Matthias Mueller, Neil Smith, Bernard Ghanem. "Context-Aware Correlation Filter Tracking." CVPR (2017 oral). [paper] [project] [code]
    RaF: Le Zhang, Jagannadan Varadarajan, Ponnuthurai Nagaratnam Suganthan, Narendra Ahuja and Pierre Moulin "Robust Visual Tracking Using Oblique Random Forests." CVPR (2017). [paper] [project] [code]
    MCPF: Tianzhu Zhang, Changsheng Xu, Ming-Hsuan Yang. "Multi-task Correlation Particle Filter for Robust Visual Tracking ." CVPR (2017). [paper] [project] [code]
    ACFN: Jongwon Choi, Hyung Jin Chang, Sangdoo Yun, Tobias Fischer, Yiannis Demiris, and Jin Young Choi. "Attentional Correlation Filter Network for Adaptive Visual Tracking." CVPR (2017) [paper] [project] [test code)] [training code]
    LMCF: Mengmeng Wang, Yong Liu, Zeyi Huang. "Large Margin Object Tracking with Circulant Feature Maps." CVPR (2017). [paper] [zhihu]
    ADNet: Sangdoo Yun, Jongwon Choi, Youngjoon Yoo, Kimin Yun, Jin Young Choi. "Action-Decision Networks for Visual Tracking with Deep Reinforcement Learning ." CVPR (2017). [paper] [project]
    CSR-DCF: Alan Lukežič, Tomáš Vojíř, Luka Čehovin, Jiří Matas, Matej Kristan. "Discriminative Correlation Filter with Channel and Spatial Reliability." CVPR (2017). [paper][code]
    BACF: Hamed Kiani Galoogahi, Ashton Fagg, Simon Lucey. "Learning Background-Aware Correlation Filters for Visual Tracking." CVPR (2017). [paper]
    Bohyung Han, Jack Sim, Hartwig Adam "BranchOut: Regularization for Online Ensemble Tracking with Convolutional Neural Networks." CVPR (2017).
    SANet: Heng Fan, Haibin Ling. "SANet: Structure-Aware Network for Visual Tracking." CVPRW (2017). [paper] [project] [code]
    DNT: Zhizhen Chi, Hongyang Li, Huchuan Lu, Ming-Hsuan Yang. "Dual Deep Network for Visual Tracking." TIP (2017). [paper]
    DRT: Junyu Gao, Tianzhu Zhang, Xiaoshan Yang, Changsheng Xu. "Deep Relative Tracking." TIP (2017). [paper]
    BIT: Bolun Cai, Xiangmin Xu, Xiaofen Xing, Kui Jia, Jie Miao, Dacheng Tao. "BIT: Biologically Inspired Tracker." TIP (2016). [paper] [project] [github]
    SiameseFC: Luca Bertinetto, Jack Valmadre, João F. Henriques, Andrea Vedaldi, Philip H.S. Torr. "Fully-Convolutional Siamese Networks for Object Tracking." ECCV workshop (2016). [paper] [project] [github]
    GOTURN: David Held, Sebastian Thrun, Silvio Savarese. "Learning to Track at 100 FPS with Deep Regression Networks." ECCV (2016). [paper] [project] [github]
    C-COT: Martin Danelljan, Andreas Robinson, Fahad Khan, Michael Felsberg. "Beyond Correlation Filters: Learning Continuous Convolution Operators for Visual Tracking." ECCV (2016). [paper] [project] [github]
    CF+AT: Adel Bibi, Matthias Mueller, and Bernard Ghanem. "Target Response Adaptation for Correlation Filter Tracking." ECCV (2016). [paper] [project]
    MDNet: Nam, Hyeonseob, and Bohyung Han. "Learning Multi-Domain Convolutional Neural Networks for Visual Tracking." CVPR (2016). [paper] [VOT_presentation] [project] [github]
    SINT: Ran Tao, Efstratios Gavves, Arnold W.M. Smeulders. "Siamese Instance Search for Tracking." CVPR (2016). [paper] [project]
    SCT: Jongwon Choi, Hyung Jin Chang, Jiyeoup Jeong, Yiannis Demiris, and Jin Young Choi. "Visual Tracking Using Attention-Modulated Disintegration and Integration." CVPR (2016). [paper] [project]
    STCT: Lijun Wang, Wanli Ouyang, Xiaogang Wang, and Huchuan Lu. "STCT: Sequentially Training Convolutional Networks for Visual Tracking." CVPR (2016). [paper] [github]
    SRDCFdecon: Martin Danelljan, Gustav Häger, Fahad Khan, Michael Felsberg. "Adaptive Decontamination of the Training Set: A Unified Formulation for Discriminative Visual Tracking." CVPR (2016). [paper] [project]
    HDT: Yuankai Qi, Shengping Zhang, Lei Qin, Hongxun Yao, Qingming Huang, Jongwoo Lim, Ming-Hsuan Yang. "Hedged Deep Tracking." CVPR (2016). [paper] [project]
    Staple: Luca Bertinetto, Jack Valmadre, Stuart Golodetz, Ondrej Miksik, Philip H.S. Torr. "Staple: Complementary Learners for Real-Time Tracking." CVPR (2016). [paper] [project] [github]
    DLSSVM: Jifeng Ning, Jimei Yang, Shaojie Jiang, Lei Zhang and Ming-Hsuan Yang. "Object Tracking via Dual Linear Structured SVM and Explicit Feature Map." CVPR (2016). [paper] [code] [project]
    CNT: Kaihua Zhang, Qingshan Liu, Yi Wu, Minghsuan Yang. "Robust Visual Tracking via Convolutional Networks Without Training." TIP (2016). [paper] [code]
    DeepSRDCF: Martin Danelljan, Gustav Häger, Fahad Khan, Michael Felsberg. "Convolutional Features for Correlation Filter Based Visual Tracking." ICCV workshop (2015). [paper] [project]
    SRDCF: Martin Danelljan, Gustav Häger, Fahad Khan, Michael Felsberg. "Learning Spatially Regularized Correlation Filters for Visual Tracking." ICCV (2015). [paper] [project]
    CNN-SVM: Seunghoon Hong, Tackgeun You, Suha Kwak and Bohyung Han. "Online Tracking by Learning Discriminative Saliency Map with Convolutional Neural Network ." ICML (2015) [paper] [project]
    CF2: Chao Ma, Jia-Bin Huang, Xiaokang Yang and Ming-Hsuan Yang. "Hierarchical Convolutional Features for Visual Tracking." ICCV (2015) [paper] [project] [github]
    FCNT: Lijun Wang, Wanli Ouyang, Xiaogang Wang, and Huchuan Lu. "Visual Tracking with Fully Convolutional Networks." ICCV (2015). [paper] [project] [github]
    LCT: Chao Ma, Xiaokang Yang, Chongyang Zhang, Ming-Hsuan Yang. "Long-term Correlation Tracking." CVPR (2015). [paper] [project] [github]
    RPT: Yang Li, Jianke Zhu and Steven C.H. Hoi. "Reliable Patch Trackers: Robust Visual Tracking by Exploiting Reliable Patches." CVPR (2015). [paper] [github]
    CLRST: Tianzhu Zhang, Si Liu, Narendra Ahuja, Ming-Hsuan Yang, Bernard Ghanem.
    "Robust Visual Tracking Via Consistent Low-Rank Sparse Learning." IJCV (2015). [paper] [project] [code]
    DSST: Martin Danelljan, Gustav Häger, Fahad Shahbaz Khan and Michael Felsberg. "Accurate Scale Estimation for Robust Visual Tracking." BMVC (2014). [paper] [PAMI] [project]
    MEEM: Jianming Zhang, Shugao Ma, and Stan Sclaroff. "MEEM: Robust Tracking via Multiple Experts using Entropy Minimization." ECCV (2014). [paper] [project]
    TGPR: Jin Gao, Haibin Ling, Weiming Hu, Junliang Xing. "Transfer Learning Based Visual Tracking with Gaussian Process Regression." ECCV (2014). [paper] [project]
    STC: Kaihua Zhang, Lei Zhang, Ming-Hsuan Yang, David Zhang. "Fast Tracking via Spatio-Temporal Context Learning." ECCV (2014). [paper] [project]
    SAMF: Yang Li, Jianke Zhu. "A Scale Adaptive Kernel Correlation Filter Tracker with Feature Integration." ECCV workshop (2014). [paper] [github]
    KCF: João F. Henriques, Rui Caseiro, Pedro Martins, Jorge Batista. "High-Speed Tracking with Kernelized Correlation Filters." TPAMI (2015). [paper] [project]


Others

    Re3: Daniel Gordon, Ali Farhadi, Dieter Fox. "Re3 : Real-Time Recurrent Regression Networks for Object Tracking." arXiv (2017). [paper] [code]
    DCFNet: Qiang Wang, Jin Gao, Junliang Xing, Mengdan Zhang, Weiming Hu. "Modeling and Propagating CNNs in a Tree Structure for Visual Tracking." arXiv (2017). [paper] [code]
    TCNN: Hyeonseob Nam, Mooyeol Baek, Bohyung Han. "Modeling and Propagating CNNs in a Tree Structure for Visual Tracking." arXiv (2016). [paper] [code]
    RDT: Janghoon Choi, Junseok Kwon, Kyoung Mu Lee. "Visual Tracking by Reinforced Decision Making." arXiv (2017). [paper]
    MSDAT: Xinyu Wang, Hanxi Li, Yi Li, Fumin Shen, Fatih Porikli . "Robust and Real-time Deep Tracking Via Multi-Scale Domain Adaptation." arXiv (2017). [paper]
    RLT: Da Zhang, Hamid Maei, Xin Wang, Yuan-Fang Wang. "Deep Reinforcement Learning for Visual Object Tracking in Videos." arXiv (2017). [paper]
    SCF: Wangmeng Zuo, Xiaohe Wu, Liang Lin, Lei Zhang, Ming-Hsuan Yang. "Learning Support Correlation Filters for Visual Tracking." arXiv (2016). [paper] [project]
    DMSRDCF: Susanna Gladh, Martin Danelljan, Fahad Shahbaz Khan, Michael Felsberg. "Deep Motion Features for Visual Tracking." ICPR Best Paper (2016). [paper]
    CRT: Kai Chen, Wenbing Tao. "Convolutional Regression for Visual Tracking." arXiv (2016). [paper]
    BMR: Kaihua Zhang, Qingshan Liu, and Ming-Hsuan Yang. "Visual Tracking via Boolean Map Representations." arXiv (2016). [paper]
    YCNN: Kai Chen, Wenbing Tao. "Once for All: a Two-flow Convolutional Neural Network for Visual Tracking." arXiv (2016). [paper]
    Learnet: Luca Bertinetto, João F. Henriques, Jack Valmadre, Philip H. S. Torr, Andrea Vedaldi. "Learning feed-forward one-shot learners." NIPS (2016). [paper]
    ROLO: Guanghan Ning, Zhi Zhang, Chen Huang, Zhihai He, Xiaobo Ren, Haohong Wang. "Spatially Supervised Recurrent Convolutional Neural Networks for Visual Object Tracking." arXiv (2016). [paper] [project] [github]
    Yao Sui, Ziming Zhang, Guanghui Wang, Yafei Tang, Li Zhang. "Real-Time Visual Tracking: Promoting the Robustness of Correlation Filter Learning." ECCV (2016). [paper] [project]
    Yao Sui, Guanghui Wang, Yafei Tang, Li Zhang. "Tracking Completion." ECCV (2016). [paper] [project]
    EBT: Gao Zhu, Fatih Porikli, and Hongdong Li. "Beyond Local Search: Tracking Objects Everywhere with Instance-Specific Proposals." CVPR (2016). [paper] [exe]
    RATM: Samira Ebrahimi Kahou, Vincent Michalski, Roland Memisevic. "RATM: Recurrent Attentive Tracking Model." arXiv (2015). [paper] [github]
    DAT: Horst Possegger, Thomas Mauthner, and Horst Bischof. "In Defense of Color-based Model-free Tracking." CVPR (2015). [paper] [project] [code]
    RAJSSC: Mengdan Zhang, Junliang Xing, Jin Gao, Xinchu Shi, Qiang Wang, Weiming Hu. "Joint Scale-Spatial Correlation Tracking with Adaptive Rotation Estimation." ICCV workshop (2015). [paper] [poster]
    SO-DLT: Naiyan Wang, Siyi Li, Abhinav Gupta, Dit-Yan Yeung. "Transferring Rich Feature Hierarchies for Robust Visual Tracking." arXiv (2015). [paper] [code]
    DLT: Naiyan Wang and Dit-Yan Yeung. "Learning A Deep Compact Image Representation for Visual Tracking." NIPS (2013). [paper] [project] [code]
    Naiyan Wang, Jianping Shi, Dit-Yan Yeung and Jiaya Jia. "Understanding and Diagnosing Visual Tracking Systems." ICCV (2015). [paper] [project] [code]
    Dataset-MoBe2016: Luka Čehovin, Alan Lukežič, Aleš Leonardis, Matej Kristan. "Beyond standard benchmarks: Parameterizing performance evaluation in visual object tracking." arXiv (2016). [paper]
    Dataset-UAV123: Matthias Mueller, Neil Smith and Bernard Ghanem. "A Benchmark and Simulator for UAV Tracking." ECCV (2016) [paper] [project] [dataset]
    Dataset-TColor-128: Pengpeng Liang, Erik Blasch, Haibin Ling. "Encoding color information for visual tracking: Algorithms and benchmark." TIP (2015) [paper] [project] [dataset]
    Dataset-NUS-PRO: Annan Li, Min Lin, Yi Wu, Ming-Hsuan Yang, and Shuicheng Yan. "NUS-PRO: A New Visual Tracking Challenge." PAMI (2015) [paper] [project] [Data_360(code:bf28)] [Data_baidu]] [View_360(code:515a)] [View_baidu]]
    Dataset-PTB: Shuran Song and Jianxiong Xiao. "Tracking Revisited using RGBD Camera: Unified Benchmark and Baselines." ICCV (2013) [paper] [project] [5 validation] [95 evaluation]
    Dataset-ALOV300+: Arnold W. M. Smeulders, Dung M. Chu, Rita Cucchiara, Simone Calderara, Afshin Dehghan, Mubarak Shah. "Visual Tracking: An Experimental Survey." PAMI (2014) [paper] [project] Mirror Link:ALOV300++ Dataset Mirror Link:ALOV300++ Groundtruth
    Dataset-DTB70: Siyi Li, Dit-Yan Yeung. "Visual Object Tracking for Unmanned Aerial Vehicles: A Benchmark and New Motion Models." AAAI (2017) [paper] [project] [dataset]
    Dataset-VOT: [project]

[VOT13_paper_ICCV]The Visual Object Tracking VOT2013 challenge results

[VOT14_paper_ECCV]The Visual Object Tracking VOT2014 challenge results

[VOT15_paper_ICCV]The Visual Object Tracking VOT2015 challenge results

[VOT16_paper_ECCV]The Visual Object Tracking VOT2016 challenge results


OTB Results


Benchmark Results

The trackers are ordered by the average overlap scores.

    AUC and Precision are the standard metrics.



Distinguished Researchers & Teams

Distinguished visual tracking researchers who have published +3 papers which have a major impact on the field of visual tracking and are still active in the field of visual tracking.(Names listed in no particular order, I will continue to supplement this part.)

Ming-Hsuan YangHaibin LingHuchuan LuHongdong LiLei ZhangXiaogang WangMatej KristanJoão F. HenriquesMartin DanelljanKaihua ZhangLuca BertinettoTianzhu ZhangTorr Vision GroupComputer Vision Laboratory, POSTECH
Benchmark

    Wu, Yi, Jongwoo Lim, and Minghsuan Yang. "Online Object Tracking: A Benchmark." CVPR (2013). [paper]
    Wu, Yi, Jongwoo Lim, and Minghsuan Yang. "Object Tracking Benchmark." TPAMI (2015). [paper] [project]
