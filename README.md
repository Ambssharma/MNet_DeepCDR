# MNet_CDR_Seg

Code for TMI 2018 "Joint Optic Disc and Cup Segmentation Based on Multi-label Deep Network and Polar Transformation"

Project homepage：http://hzfu.github.io/proj_glaucoma_fundus.html

1. The code is based on: *Keras 2.0 + Tensorflow*
2. The output is raw segmentation result without ellipse fitting.
3. The code including (A) disc detection and (B) Disc/Cup segmentation. 
3. The pre-train models *'Model_DiscSeg_ORIGA_pretrain.h5'* and *'Model_MNet_ORIGA_pretrain.h5'* is trained on **ORIGA full dataset**.
4. Please cite the following papers:

[1] Huazhu Fu, Jun Cheng, Yanwu Xu, Damon Wing Kee Wong, Jiang Liu, and Xiaochun Cao, "Joint Optic Disc and Cup Segmentation Based on Multi-label Deep Network and Polar Transformation", IEEE Transactions on Medical Imaging (TMI), 2018. DOI: 10.1109/TMI.2018.2791488 (ArXiv version: https://arxiv.org/abs/1801.00926) 

[2] Huazhu Fu, Jun Cheng, Yanwu Xu, Changqing Zhang, Damon Wing Kee Wong, Jiang Liu, Xiaochun Cao, "Disc-aware Ensemble Network for Glaucoma Screening from Fundus Image", IEEE Transactions on Medical Imaging (TMI), 2018. DOI: 10.1109/TMI.2018.2837012 (ArXiv version: http://arxiv.org/abs/1805.07549)


----------------

Update log:

- 18.06.29: Added disc detection code (based on U-Net)
- 18.02.26: Added CDR calculation code (based on Matlab)
- 18.02.24: Released the code

