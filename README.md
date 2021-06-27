# Diseased and Healthy Mango Leaves Classification

### Objective
Classification of diseased and healthy mango leaves using pre-trained ResNet-50 model

### Approach
I have made use of pre-trained ResNet-50 model for classification of a mango leaf as diseased or healthy. 

#### Methodology
Contrast enhancement using CLAHE is initially performed, and the images are stored. These images are then loaded and resized to (224 x 224). Label encoding is performed, followed by feature extraction using a pre-trained ResNet-50 model. The head model is not included, and a customized head model is appended with the pre-trained ResNet-50 model. Using this model, the classification of diseased and healthy mango leaves in done.

The model has achieved an accuracy of 97.7%. 

And the training and validation plots are as follows.

![Training and Validation Accuracy](https://github.com/SandhyaSridhar/DiseasedMangoLeavesDetection/blob/main/Training%20and%20Validation%20Accuracy.JPG)
![Training and Validation Loss](https://github.com/SandhyaSridhar/DiseasedMangoLeavesDetection/blob/main/Training%20and%20Validation%20Loss.JPG)

Secondly using ML classifiers like LR, KNN, SVM etc, feature extraction is initially done using pre-trained ResNet-50 model. And the following are the results obtained

| Classifier      | Accuracy  | 
| -------------   |:---------:| 
| KNN Classifier  | 83.91 %   |
| Gaussian Naive Bayes Classifier  | 87.36 %   |
| Logistic Regression  | 98.85 %   |
| Decision Tree Classifier  | 91.95 %   |
| SVM Classifier  | 98.85 %   |
| Gradient Boosting Classifier| 94.25 %   |
| XGBoost Classifier  | 97.7 %   |


### Dataset
I have made use of the Mango leaves dataset from Data Medely. You can access the dataset from this [link](https://data.mendeley.com/datasets/hb74ynkjcn/1)

