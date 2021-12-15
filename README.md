# DSCamp
# Abstract:
Naturally diagnosing diseases requires effort, time, and people specialized in the field, and the possibility of human error in diagnosis is very high. Therefore, the need for an automated system for diagnosis has increased. One of the most dangerous diseases worlds around is Malaria, which could infect humans with parasites that are transmitted through the bites of infected female Anopheles mosquitoes. where the estimated deaths in 2019 reached about 409000 cases. Based on the purpose of early diagnosing of malaria this project proposed. In this project I Implement the classification using the convolution neural network CNN with two different training strategies, the first model is the pre-trained CNN model (MobileNetV2) and the second model is CNN with training over the dataset from scratch the second model achieves an accuracy of 96%. the result shows that we can take the advantage of using deep learning as diagnosing tool to help those in the medical field for easy and accurate diagnosis the malaria disease.
# Data:
The used dataset is microscopic cells images (27,558 cell images), labelled to parasitized(abnormal) and uninfected cells(normal), this dataset was collected by developing a mobile application that runs on a standard Android smartphone attached to a conventional light microscope. The dataset is uploaded in [Kaggle](https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria) . The dataset is a balanced dataset where the number of image samples of the parasitized class is the same as the number of uninfected classes which equal 13779 images
# Tools:
•Dataset preprocessing and importing : os, numpy,pandas, split-folders

•	Models building and performance evaluation : tensorflow,keras, sklearn

•	Visualization: matplotlib, seaborn, slide show
# Usage:
1- Uplode the dataset from [kaggle](https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria).

2- Uplode the [Malaria_Diagnosis_project.ipynb](https://github.com/manarSaad1/DSCamp/blob/main/Malaria_Diagnosis_project%20.ipynb)

3- Change the path of the dataset to your own path and be sure you have all the mentioned packages to run the code correctly.

