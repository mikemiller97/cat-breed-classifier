# 🐾 Cat Breed Classifier

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1dxBnwJNSKIFIczWtxRW4Ie1M12e4xMij)

This project is a **multi-class cat breed classifier** capable of identifying cats across **50+ breeds**.  
It combines **object detection** and **image classification** into a streamlined pipeline:

- **Preprocessing Pipeline** – Prepares input images for detection and classification.  
- **YOLOv8 Detector** – Scans the input image to detect cats. If a cat is present, it automatically crops the image around the detected cat.  
- **MobileNet Classifier** – Takes the cropped image and predicts the breed from over 50 possible categories.  

---

## ✨ Key Features
- End-to-end pipeline from raw image → detection → breed prediction  
- Robust to images containing multiple objects or background clutter thanks to YOLOv8  
- Lightweight and efficient classification with MobileNet, optimized for deployment  
- Outputs **top 3 breed predictions** with associated confidence scores 

---

## 🔄 Example Workflow
1. Upload an image  
2. YOLOv8 checks for the presence of a cat and crops the image if detected  
3. MobileNet predicts the breed of the detected cat  

---

## 📌 Potential Use Cases
- **Veterinarians** – Quickly identify cat breeds in clinics or when working with strays  
- **Animal Shelters & Adoption Agencies** – Assist in cataloging and labeling cats for adoption listings  
- **Pet Owners** – Learn more about their cat’s background or confirm breed information  
- **Researchers** – Study breed distribution and traits using large image datasets  

---

## 🚀 Future Improvements
- Support for additional breeds   
- Deployment on mobile or web applications for real-time use  

