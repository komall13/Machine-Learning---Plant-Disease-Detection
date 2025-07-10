# Machine-Learning----Plant-Disease-Detection
Plant Disease Detection using Machine Learning
This project focuses on building a Convolutional Neural Network (CNN) model to automatically detect bacterial diseases in plants by analyzing leaf images. It aims to support early diagnosis and treatment in agriculture by classifying diseases across different crop types.

###Project Objective
To develop an image classification model that can accurately detect plant diseases from leaf images for three major crops:
Potato
Tomato
Corn
Each category includes images of leaves affected by bacterial infections, making it a real-world application of machine learning in agriculture and plant pathology.

###Dataset Structure
The dataset is divided into two sets:
Training Set (train/): Contains a large number of images categorized into:
potato/
tomato/
corn/
Note: Due to large size, the training images are uploaded directly to GitHub without enclosing the folder.
Testing Set (test/): Includes a smaller number of images in a structured folder named test/, with the same subfolders:
potato/
tomato/
corn/
Each subfolder contains photographs of infected leaves representing bacterial diseases.

🛠️ Tools & Technologies
Google Colab (development and training)
Python (programming language)
TensorFlow / Keras (deep learning framework)
OpenCV / PIL (image processing)
Matplotlib / Seaborn (visualization)

###Workflow
###Data Preprocessing
Image resizing and normalization
Data augmentation for better generalization

###Model Building
Custom CNN architecture or pretrained models (e.g., MobileNet, VGG16)
Trained using categorical crossentropy and Adam optimizer

###Training & Evaluation
Trained on the train/ dataset
Evaluated using the test/ dataset
Metrics: Accuracy, Precision, Recall, and Confusion Matrix

###Prediction
Predicts plant type and bacterial infection based on input leaf images

###GitHub Note
The test/ dataset is uploaded in a folder for direct access.
The train/ dataset is large and uploaded as individual files in GitHub root (without folder).

###Outcome
The trained model effectively classifies bacterial leaf infections across different plant types, helping demonstrate the role of AI in smart agriculture and crop health monitoring.
