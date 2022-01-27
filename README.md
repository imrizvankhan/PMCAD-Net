# PMCAD-Net
 Practical Multiclass Classification Network for Diagnosis of Alzheimer’s Disease
 
 
Requirements Python  Pytorch = 1.10.0 numpy

Descriptions: This project shows the prelimenary implementation guidelines for the Practical Multiclass Classification Network for Diagnosis of Alzheimer’s Disease(PMCAD-Net). We aim to improve the performance of the detection of the  AD in the presence of small dataset. We propose a feed-forward network to detect various dementia. We propose to learn through the consistency of the pre-processed data. We utilize the Alzheimer's Disease Neuroimaging Initiative (ADNI) data set.

Dataset:
The dataest obtained through ADNI is pre-proesses and the effective slices are extracted from the 3D-Niftii volumes. The 2D portable network graphics are resized and fed to the network for the training.
The datasets used for comparison include OASIS, ADNI, and Kaggele datasets.  We presented evaluation on test images from our data set. We have presented the results for test classes.  The test images classify the Normal control, Early Mild Cognitive Impairment, Late Mild Cognitive Impairment, and Alzhmier disease. 
Dataset-Link: data set http://adni.loni.usc.edu/


<img src="https://github.com/imrizvankhan/PMCAD-Net/blob/main/PMCAD-Net%20results/Preprocessing%2Bframework.png">
<img src="https://github.com/imrizvankhan/PMCAD-Net/blob/main/PMCAD-Net%20results/Network%2Bframework2.png" height = 400 width = 700>

<img src="https://github.com/imrizvankhan/PMCAD-Net/blob/main/PMCAD-Net%20results/3-view-1.png" height = 300 width = 600>

<img src="https://github.com/imrizvankhan/PMCAD-Net/blob/main/PMCAD-Net%20results/Box-Plots-G1-4.png" height = 400 width = 700>
