# Segmentation of Intra-Retinal Cysts (IRC) from OCT scans using Fully Convolutional Neural Network (FCN)

### Overview 

This repository provides an implementation of an FCN model-based vendor independent IRC segmentation technique. The proposed FCN model is trained with preprocessed OCT scans from four different vendors (namely, Cirrus, Nidek, Spectralis, and Topcon). The preprocessing is performed as described in [1]. The method is trained and validated on the OPTIMA cyst segmentation challenge dataset [2]. The proposed model achieves a dice score of 0.73 on G3, 0.72 on G2 and 0.71 on G1 where G1, G2 and G3 represent Grader 1,Grader 2 and intersection of G1 and G2 respectively. 

## Pre-requistes Required

1.Tensorflow

Refer to the following link https://www.tensorflow.org/install/install_sources. Tensorflow is used as backend for Keras. The link contains installation instructions with and without gpu support

2.Keras

To install Keras: sudo pip install keras

3.Jupyter Notebook

Refer following link for installation instructions https://www.digitalocean.com/community/tutorials/how-to-set-up-a-jupyter-notebook-to-run-ipython-on-ubuntu-16-04


### References

[1] Girish, G. N., et al. "Segmentation of Intra-Retinal Cysts from Optical Coherence Tomography Images using a Fully Convolutional Neural Network Model." IEEE Journal of Biomedical and Health Informatics (2018).

[2] “Optima cyst segmentation challenge,” 2015. [Online]. Available: https://optima.meduniwien.ac.at/research/challenges/
