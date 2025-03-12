# 🚦 **Traffic Sign Classification using Transformers**  

## 📌 **Project Overview**  
This project aims to classify **traffic signs** using a **hybrid deep learning model** that integrates:  
🔹 **YOLOv5** 🏎️ – For object detection and localization of traffic signs.  
🔹 **Channel Attention Mechanism** 🔍 – To enhance feature extraction and improve detection accuracy.  
🔹 **Transformers** 🤖 – For robust classification of traffic signs.  

## 📂 **Dataset Used**  
📌 **[Specify Dataset Name]** – Contains labeled traffic sign images for training and evaluation.  

## 🔄 **Workflow**  
1️ **Data Preprocessing** 🛠️  
   - Image resizing, normalization, and augmentation.  
   - Dataset splitting into **training, validation, and test sets**.  

2️ **Feature Extraction** 🎯  
   - YOLOv5 for **object detection** and **bounding box localization**.  
   - Channel Attention for **better feature refinement**.  

3️ **Classification using Transformers** 🚀  
   - Uses **Vision Transformers (ViT)** for **final classification**.  

4️ **Training & Evaluation** 📊  
   - **Loss function:** *[Specify loss function]*  
   - **Metrics:** Accuracy, Precision, Recall, F1-score  
   - **Evaluation on test set** with confusion matrix and classification report.  

## 🎯 **Results & Insights**  
🔹 **High accuracy** in traffic sign detection and classification.  
🔹 **YOLOv5 + Channel Attention** improves object detection robustness.  
🔹 **Transformers** enhance classification performance.  

## 🚀 **Future Enhancements**  
- 🔹 Train on **larger datasets** for better generalization.  
- 🔹 Implement **real-time classification** for self-driving applications.  
- 🔹 Optimize the model for **edge devices (Raspberry Pi, Jetson Nano, etc.)**.  
