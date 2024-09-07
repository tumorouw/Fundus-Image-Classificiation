# Fundus Image Classification
*The increase in age in a population results in cases of visual impairment that cause blindness, so the World Health Organization (WHO) released a report that directs to collect, analyze, and use data from eye health, one of which is the fundus image collected through a camera. These images have been used by ophthalmologists in diagnosing and screening eye diseases. Deep learning technology especially with CNN for classification can be used to assist doctors in diagnosis. One of the tasks of computer vision (CV) is classification so that it can be applied by creating a model capable of classification with CNN architectures in the form of VGG-19, EfficientNet-B3, ResNet-50, and Xception and custom layers by applying preprocessing to datasets that have been divided into training, validation, and testing as well as augmentation of training data. The ResNet-50 model is the best in classifying fundus images into four classes, namely cataract, diabetic retinopathy, glaucoma, and normal with a recall score and F1-score of 92% each, while Xception is the best model in finding positive cases in the disease class with an average recall score of 90.67%.*

# The Dataset
The dataset consist of 4 folders, which is Cataract, Diabetic Rethinopaty, Glaucoma and Normal. The Dataset is retrieved from Kaggle with 1074 images for normal class, cataract 1038, glaucoma 1007, and Diabetic Rethinopaty with 1098 images.
https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification

![image](https://github.com/user-attachments/assets/c804e71b-f461-4473-a649-1e18183745fc)

# The Purpose 
1.	Designing a deep learning model by utilizing CNN architecture and custom layers that can classify fundus images.
2.	Measuring the performance of deep learning models with CNN architecture and custom layers in classifying fundus images.

# Scope
1. The fundus dataset was obtained through Kaggle created by Gunna Venkat Doddi and last updated in 2022.
2. The dataset consists of four classes, namely normal, cataract, glaucoma, and diabetic retinopathy. The number of samples from the dataset is 4217 with 1074 normal, 1038 cataract, 1007 glaucoma, and 1098 diabetic retinopathy.
3. The CNN architecture types used are VGG-19, ResNet-50, EfficientNetB3, and Xception with weights from ImageNet.
4. The custom layers used consist of global average pooling, two dense layers, two dropout layers, and output layers for four classes.
5. The dataset will be applied preprocessing by resizing the image to 224 x 224 pixels and applying the CLAHE function.
6. The dataset will be divided into three parts, namely training data, validation data, and testing data with a ratio of 70:15:15.
7. Training data will be applied augmentation in the form of horizontal flip, rotation, and zoom with each augmentation of 0.1.
8. Measuring model performance using precision, recall, F1-score, and accuracy.
9. Apply Grad-CAM to see the features captured by the model in making predictions.

# Conclusion and Suggestions
1.	A deep learning model with CNN architecture and custom layers was successfully designed using VGG-19, EfficientNet-B3, ResNet-50, and Xception and custom layers consisting of global average pooling, two dense layers, two dropout layers, and one output layer for four-class prediction with fixed ImageNet weights. The dataset is preprocessed and then divided into training, validation, and testing with a ratio of 70:15:15 and then augmentation is applied to the training data.
2.	The performance of deep learning models with CNN architecture and custom layer was successfully measured using accuracy and F1-score metrics with the ResNet-50 model as the best with a score of 92% respectively, while when considering the ability of the model to find positive cases in disease classes, the Xception model is the best with an average recall score of 90.67% in cataract, diabetic retinopathy, and normal classes.
