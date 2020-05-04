# Chest X-Ray Image Classification

This repository contains a very basic code to perform deep learning on Chest X-Ray images obtained from various sources and classifying them into COVID-19, Pneumonia and Normal using Pytorch and fastai library. No cleaning and optimization has been done so far, as this is a learning exercise I have done after the first lesson of the course Practical Deep Learning for Coders v3. I will work on this further to improve as I learn from the following lessons of the course. 

## Datasets
Following are the datasets I used for collecting the CXR images :
1. [ChestXray-NIHCC](https://nihcc.app.box.com/v/ChestXray-NIHCC/folder/36938765345)
2. https://github.com/ieee8023/covid-chestxray-dataset
3. https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

For the purpose of this exercise, I excluded Axial, Coronal, L, AP Semi Erect images. All the images are stored in Google Cloud Storage and the training is done on a Google Compute Engine VM Instance.

## References 
1. https://towardsdatascience.com/using-deep-learning-to-detect-ncov-19-from-x-ray-images-1a89701d1acd
2. https://github.com/lindawangg/COVID-Net
3. https://docs.fast.ai/
