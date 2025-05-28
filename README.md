# Brain-Tumor-Classification (CNN)


This is a personal project where I built a deep learning model to classify brain MRI images into different tumor types. I used a dataset from Kaggle and resized the images to 224x224 pixels so they could be used with a pretrained ResNet50 model.

I split the data into training, validation, and test sets (70%, 15%, 15%) and trained the model using TensorFlow and Keras. I fine-tuned the ResNet50 model and added some custom layers to improve accuracy and reduce overfitting.

To evaluate the model, I looked at accuracy, confusion matrices, precision, recall, F1 scores, ROC curves, and precision-recall curves. I also used TensorBoard and a learning rate scheduler to monitor and improve training.

This project helped me get more hands-on experience with CNNs and medical image classification.

# Class/Test Distribution
<img src="https://github.com/jfherrera02/Brain-Tumor-Classification/blob/main/images/distribution.png?raw=true" alt="Dataset distribution" width="700"/>

# Model Architecture
<img src="https://github.com/jfherrera02/Brain-Tumor-Classification/blob/main/images/model.png?raw=true" alt="Model architecture" width="600"/>


# Performance Matrix
<img src="https://github.com/jfherrera02/Brain-Tumor-Classification/blob/main/images/Brain-tumor-performance-matrix.png?raw=true" alt="Performance matrix" width="500"/>
