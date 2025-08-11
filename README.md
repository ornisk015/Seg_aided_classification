# Seg_aided_classification
Skin cancer, particularly melanoma, poses a critical
global health concern. Early detection is essential, yet the
complexity of dermoscopic image analysis remains a significant
challenge due to irregular lesion morphology, low contrast, and
interclasssimilarities. We propose a three-stage segmentation-
aided diagnostic framework that integrates segmentation and
classification in a unified pipeline. First, MRP-UNet performs
multiscale segmentation using MIF, Res2SE, and PDC modules.
Second, Mask-CN classifies lesions using both RGB images and
coarse masks while generating class activation maps (CAM). Fi-
nally, Enhanced-SN refines segmentation by incorporating CAMs
for boundary-aware enhancement. We evaluated our system in
the ISIC 2017 dataset, achieving an average Dice score of 0.8712
and a Jaccard index of 0.7965 for 5-fold cross-validation in
segmentation, and 73% test accuracy in mask-informed clas-
sification.
