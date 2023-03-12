# Cotton-disease-Prediction-CNN

EASY WAY TO WATCH:

https://www.kaggle.com/code/agrinurture/cotton-disease-prediction-cnn

OR:

Download the cotton-disease-prediction-cnn.ipynb 

Data science perspective:

- Data based on 4 classes:
- diseased cotton leaf.
- diseased cotton plant.
- fresh cotton leaf.
- fresh cotton plant.

The data set - a set of images from the Kaggle database. The set is divided into 4 categories: leaf with disease, leaf without disease. Bush with disease, bush without disease.
A total of 2300 photos, of which 1270 are about 55% with diseases and the rest without diseases. Training 80% and conditioning 10%, test 10%, while maintaining a ratio of approximately one quarter in each group.
The images are colored and their size is height-256 length-256 color method-RGB(3).

Data Augmentation:

- Data augmentation was used. The types of augmentation are change of height, length, rotation, zoom, applying colors and flipping.

 ![image](https://user-images.githubusercontent.com/109544498/224564259-b420fb09-3ba2-4404-8ebb-166d7d4e8493.png)

Model Tested:
- Base Model with 2 Convolution layers.
- VGG-16 With Transfer learning.(Best result 98% acc)

![image](https://user-images.githubusercontent.com/109544498/224576792-3e73764a-3244-4a81-9661-9792e3475cbc.png)


- VGG-19 With Transfer learning.
- ResNet50 With Transfer learning.
- MobileNetV2.(Top Result 92% acc suitble for mobile dev light Weight and fast)

![image](https://user-images.githubusercontent.com/109544498/224576847-da0c7fd4-b6da-40f5-ab7a-260cfe19c439.png)


![image](https://user-images.githubusercontent.com/109544498/224576661-1aaca4f0-14f3-4b53-b516-cec998650dbc.png)



Summary:
In conclusion, it can be seen that even the simplest model with 2 convolution layers gives us results of over 95 percent in both testing and validation.
But the model with the best results is VGG-16/19 with an SGD optimizer with a learning curve of 0.001 and a momentum of 0.9 in order to overcome the local minimum problem.
This model is the model that gave the best results of 99% on the training set, although the training set is small, but the results always ranged from 0.97 to 0.99, which means that the model consistently gives reliable results.
This is a model that has undergone FINE-TUNE and weights of . IMAGENET


For more details about the project:

- Download the docx file above.

