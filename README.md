Brain Tumor Detection Using VGG-16 CNN Transfer Learning
Project Overview
This project applies Deep Learning and Computer Vision to detect brain tumors from MRI scans. A Convolutional Neural Network (CNN) based on the VGG-16 architecture is trained to classify MRI scans into two categories:
✅ No Tumor | ❌ Brain Tumor

Dataset & Preprocessing
Before training, the MRI scans undergo data preprocessing, including image cropping and augmentation to enhance model performance.

<p align="center"> <img width="750" height="200" src="Images/Data%20Preprocessing.png" alt="Data Preprocessing"> </p>
Model Architecture
The model is built using VGG-16 with transfer learning, leveraging pre-trained weights for feature extraction. The final layers are fine-tuned for binary classification. The Jupyter Notebook (Brain-Tumor-Detection-MRI-Scans.ipynb) contains the full implementation.

Results & Performance
The model achieved:

92% Accuracy on the Validation Set
80% Accuracy on the Test Set
Performance visualizations:

<p align="center"> <img width="850" height="300" src="Images/Accuracy%20&%20Loss%20Curves.png" alt="Accuracy & Loss Curves"> </p> <p align="center"> <img width="400" height="400" src="Images/Confusion%20Matrix-Validation.png" alt="Confusion Matrix - Validation"> </p> <p align="center"> <img width="400" height="400" src="Images/Confusion%20Matrix-Test.png" alt="Confusion Matrix - Test"> </p>
Example MRI Scans
<p align="center"> <img width="350" height="300" src="Images/No%20Tumor.png" alt="No Tumor"> <img width="350" height="300" src="Images/Tumor.png" alt="Tumor"> </p>
Conclusion & Future Improvements
The CNN-based model effectively classifies brain tumors from MRI scans. Future improvements include:
✔️ Expanding the dataset for better generalization
✔️ Experimenting with alternative CNN architectures (ResNet, EfficientNet)
✔️ Hyperparameter tuning for improved performance

