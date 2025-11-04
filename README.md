# 🧠 Neuro Fusion – Brain Tumor Detection Using Deep Learning

> 🎓 *Final Year B.Tech Project* | 🥇 *Best Paper Award – ICCIDS 2025* | 🧾 *Patent Filed*

Neuro Fusion is a **deep learning-based brain tumor detection system** designed to assist medical professionals in identifying and classifying brain tumors from MRI scans with high accuracy.  

Built with **Convolutional Neural Networks (CNNs)**, this system achieves **93% accuracy** on the BraTS dataset and integrates a **Django web interface** for real-time tumor prediction and visualization.

---

## 🚀 Overview

Brain tumors can be challenging to detect manually from MRI images due to varying shapes, sizes, and locations. **Neuro Fusion** leverages the power of AI and computer vision to:
- Automatically **classify MRI scans** as tumorous or non-tumorous  
- Visualize **model predictions and confidence scores**  
- Provide a **web-based interface** for doctors and researchers

  <img width="1874" height="822" alt="Screenshot 2024-10-26 134313" src="https://github.com/user-attachments/assets/5adab705-e8c1-44e5-8c2d-0c4a9fbb8197" />


This project combines **AI + healthcare**, aiming to support faster and more reliable medical diagnosis.

---

## 🧩 Features

✅ MRI brain tumor classification using CNN  
✅ High accuracy (93%) on BraTS dataset  
✅ User-friendly Django web app for predictions  
✅ Data preprocessing and augmentation for better generalization  
✅ Visualization of model performance (accuracy/loss plots)  
✅ Deployable on cloud or local systems  

---

## 🏗️ Tech Stack

| Category | Technologies |
|-----------|--------------|
| **Language** | Python |
| **Frameworks** | TensorFlow, Keras, Django |
| **Libraries** | NumPy, Pandas, OpenCV, Matplotlib, Scikit-learn |
| **Dataset** | [BraTS (Brain Tumor Segmentation Challenge)](https://www.med.upenn.edu/cbica/brats2021/data.html) |
| **Deployment** | Django Web App, Streamlit (optional) |
| **Version Control** | Git, GitHub |

---

## 🧠 Model Architecture

The CNN model consists of:
- Multiple **convolutional + pooling layers** for feature extraction  
- **Batch normalization** and **dropout** layers for stability  
- Fully connected layers for final classification  
- **Softmax activation** for output prediction


<img width="1062" height="522" alt="Screenshot 2025-01-18 162601" src="https://github.com/user-attachments/assets/389111db-4907-477a-aafd-e61fe5fcc17b" />

```python
Model Summary:
Conv2D → MaxPool → Conv2D → MaxPool → Flatten → Dense → Dropout → Output(Softmax)
