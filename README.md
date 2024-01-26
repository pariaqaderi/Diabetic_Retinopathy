# Diabetic_Retinopathy

People with diabetes may suffer from an eye complication called diabetic retinopathy, which causes blurred vision and blindness. In this project, we try to combine Deep Learning 
and Machine Learning approches to reach a suffiecient accuracy. 

## Dataset

Our dataset is from Kaggle, which has five folders and includes 370 photos of mild, 999 photos of moderate, 1805 photos of non-diabetic retinopathy, 
295 photos of proliferative diabetic retinopathy and 193 Severe Non-proliferative diabetic retinopathy. You can access the dataset via this link: 
'https://www.kaggle.com/datasets/sovitrath/diabetic-retinopathy-224x224-gaussian-filtered?select=train.csv'

## Deep Learning Approaches 

We implemented three Networks using tenserflow Libarary. 

- CNN
* VGG16
+ GoogleNet


## Machine Learning Algorithms

We used four ML Supervised Leaning methods to classify the images. In order to that, scikit-learn library can be the best choice.

- Support Vector Machine
* Decision Tree
+ K-Nearest-Neighbours
+ Naive Bayes

## Result

The combination of VGG16 and KNN with 93.19 accuracy showed the best performance.





