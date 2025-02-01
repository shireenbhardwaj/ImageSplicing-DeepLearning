# 🖼️🔍 Image Forgery Detection using Deep Learning
Detecting image splicing and copy-move forgery using deep learning to combat misinformation and cyber threats. This project utilizes VGG-16 and ResNet-101 for forgery detection and leverages the CASIA dataset. It includes image preprocessing, model training, and evaluation to enhance visual security on social media. 

## 📌 Overview
With the growing concern over image forgery in digital media, this project focuses on detecting image splicing and copy-move forgery using deep learning models. Our solution aims to enhance visual information security, particularly across social media platforms like TikTok, Facebook, Instagram, and YouTube, where manipulated images can lead to cyberbullying, misinformation, and security threats.

🚀 Key Features
Advanced Image Forgery Detection: Detects splicing and copy-move forgery in images using Convolutional Neural Networks (CNNs).
Cutting-Edge Deep Learning Models: Utilizes VGG-16 and ResNet-101 for high-accuracy predictions.
Real-World Application: Helps mitigate the spread of fake images on social media, preventing cyber threats and political manipulation.
Optimized Image Preprocessing: Includes RGB conversion, brightness scaling, resizing, and pixel-difference analysis for superior model performance.
🎯 Why This Matters?
- **Cyberbullying & Harassment:** 59% of US teens report being victims of image-based cyberbullying (Pew Research).
- **Political Manipulation:** Fake images fuel misinformation and impact elections and social trust.
- **Security Risks:** Image forgery techniques are exploited to create fake IDs, fraud documents, and financial scams.

## 📂 Dataset
**Source:** CASIA Dataset (Kaggle)
|Image type: Dataset Size|Example Image|
|:----:|:------:|
|**Tampered Images:** 5,180|<img width="559" alt="image" src="https://github.com/user-attachments/assets/fbde312d-9d1f-4b79-b41c-6d6d0ee823a2" />|
|**Authentic Images:** 7,609|<img width="596" alt="image" src="https://github.com/user-attachments/assets/c0b4295d-295b-49af-be7b-db41b00da6dd" />|

**Preprocessing:** Image conversion, compression, pixel difference analysis, brightness scaling, resizing (128×128).

## 🛠Tech Stack
Python, NumPy, Pandas, PIL (Pillow), Matplotlib, Seaborn, Keras (TensorFlow Backend), Scikit-Learn (Sklearn), Google Colab

## 📊 Data Preprocessing
|Step|What it looks like|
|:----:|:----:|
|Convert the image to RGB & compress the image|<img width="598" alt="image" src="https://github.com/user-attachments/assets/ca1927f0-91b4-4f0e-9c6b-8a02ad407c24" />|
|Calculate the Pixel Differences between the original & compressed images|<img width="750" alt="image" src="https://github.com/user-attachments/assets/3ad21618-2228-4ec2-9b32-1da94d4eacd9" />|
|Scale the Brightness of the Compressed Image|<img width="546" alt="image" src="https://github.com/user-attachments/assets/fbf31d62-7698-494f-a5e0-a0c44f4b7c40" />|
|Resize the Image (128 x 128)|<img width="511" alt="image" src="https://github.com/user-attachments/assets/4491b796-90ce-4ae0-bf04-05392a192d41" />|

## ✅ Model Validation
Since we want to focus on minimizing false negatives, our metric is **‘Recall’**.
<p align="center">
<img width="1042" alt="image" src="https://github.com/user-attachments/assets/9df005af-c2d6-471a-9b68-772a729424e7" />

<img width="630" alt="image" src="https://github.com/user-attachments/assets/70aefef0-5575-4f98-83c7-0c04e6d44c0d" />

</p>
