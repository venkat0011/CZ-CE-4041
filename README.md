# CE/CZ4041

<!-- ABOUT THE PROJECT -->
## Machine Learning

The machine learning project focuses on classifying the plant seedling into one of the 12 classes. The team managed to acheive a test score of 0.97344 putting us at 227 out of 835

The images are obtained from https://www.kaggle.com/c/plant-seedlings-classification
![image](https://user-images.githubusercontent.com/76080326/200122458-d30d2611-5853-4866-8327-23ec42b467df.png)

The image contains noisy information such as the tape, rocks. So the team performed hue-value-saturation segmentation to segment only the portion of the image that is green
![image](https://user-images.githubusercontent.com/76080326/200122508-c956fe46-eca8-46bb-b35e-d0c40454b091.png)

The team explored using different machine learning models such as K-nearest neighbours, EfficientNet,VGG16, Inception-Resnet-V2,ResNet50
To improve the model further, the output of these neural network were fed into a meta learner ( random forest) to find a function that best maps the predicted output to the actual output

![image](https://user-images.githubusercontent.com/76080326/200122651-8528fd16-30ef-474a-9ea5-e17dc622a38c.png)

