# Paddy-Diseases-Monitor-
My FYP project
Paddy Disease Monitoring System 🌾
This repository contains the code and documentation for my Final Year Project (FYP): Paddy Disease Monitoring System. The goal of this project is to leverage machine learning and computer vision to assist farmers in identifying paddy diseases early, thus improving crop yield and reducing losses.

🚀 Project Highlights
Objective: Develop a mobile application capable of detecting paddy diseases using advanced deep learning models.
Key Features:
Image-based disease detection for paddy crops.
User-friendly mobile app built with Flutter for seamless interaction.
Efficient and accurate disease classification using state-of-the-art hybrid deep learning models.
🔍 Technical Details
Dataset
The dataset comprises 15,000+ images categorized into 5 distinct classes of paddy health states.
Classes: Bacterial Leaf Blight, Brown Spot, Healthy, Leaf Blast, and Tungro.
Deep Learning Models
Explored architectures:
Pre-trained models like VGG-16, InceptionV3, EfficientNet, and ResNet.
Custom and hybrid architectures combining InceptionV3, MobileNetV2, and custom CNN layers.
Techniques:
Experimented with various activation functions (ReLU, Swish, Leaky ReLU, etc.).
Ensemble learning (soft voting, hard voting, stacking).
Performance
Achieved high accuracy and robust performance using hybrid deep learning approaches.
Evaluated models based on precision, recall, F1-score, and confusion matrix.
📱 Mobile Application
Built with Flutter for cross-platform support.
Intuitive interface to upload images and view disease predictions in real time.
Backend integration to deploy trained models for efficient inference.
🛠️ Installation and Usage
Requirements
Python 3.8+
Flutter SDK
Conda environment for model training and preprocessing.
Steps
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/paddy-disease-monitoring.git
Follow the setup instructions in the README.md files for model training and Flutter app development.
📊 Results and Analysis
Extensive experiments were conducted with various models and configurations.
The proposed hybrid model (InceptionV3 + MobileNetV2) provided the best trade-off between accuracy and computational efficiency.
🙌 Acknowledgements
Thanks to my supervisors, peers, and all contributors who supported this project.
The dataset was a critical resource for enabling this research.
