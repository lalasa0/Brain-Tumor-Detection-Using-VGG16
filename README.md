Brain Tumor Detection Using VGG-16 CNN Transfer Learning
Project Overview
This project leverages Deep Learning and Computer Vision techniques for Brain Tumor Detection using MRI scans. We implemented a Convolutional Neural Network (CNN) based on the VGG-16 architecture to classify MRI scans into two categories:
✅ No Tumor | ❌ Brain Tumor

Dataset & Preprocessing
MRI scans were preprocessed before training. Data augmentation techniques were applied to expand the dataset and improve model generalization. The images were cropped and processed as shown below:

<p align="center"> <img width="750" height="200" src = 'https://github.com/lalasa0/Brain-Tumor-Detection-Using-VGG16/blob/main/Images/Data%20Preprocessing.png?raw=true' </p>
Model Architecture
We used VGG-16 with transfer learning, utilizing pre-trained weights for feature extraction. The final layers were fine-tuned for binary classification (Tumor/No Tumor).

Results & Performance
The model achieved:

92% Accuracy on the Validation Set
80% Accuracy on the Test Set
Below are the Accuracy & Loss Curves and Confusion Matrices:

<p align="center"> <img width="850" height="300" src = 'https://github.com/lalasa0/Brain-Tumor-Detection-Using-VGG16/blob/main/Images/Accuracy%20&%20Loss%20Curves.png?raw=true' </p> <p align="center"> <img width="400" height="400" src = 'https://github.com/lalasa0/Brain-Tumor-Detection-Using-VGG16/blob/main/Images/Confusion%20Matrix-Validation.png?raw=true' </p> <p align="center"> <img width="400" height="400" src = 'https://github.com/lalasa0/Brain-Tumor-Detection-Using-VGG16/blob/main/Images/Confusion%20Matrix-Test.png?raw=true' </p>
Conclusion & Future Improvements
The CNN-based model successfully classifies Brain Tumors from MRI scans. To further improve accuracy, we can:
✔️ Use a larger dataset for training
✔️ Apply hyperparameter tuning
✔️ Experiment with other CNN architectures (ResNet, EfficientNet, etc.)
