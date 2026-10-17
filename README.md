# Face Verification & Identification System

A deep metric learning solution for face verification using a **Siamese Neural Network** trained on the **Labeled Faces in the Wild (LFW)** dataset using **PyTorch**.

---

##  Project Overview
This project focuses on face verification and distance-based metric learning. By constructing pairwise and triplet pipelines, the model learns high-quality visual embeddings to determine whether two given facial images belong to the same individual.

---

##  Key Features
- **Siamese Network Pipeline:** Programmatically filtered the raw LFW dataset and built paired/triplet input pipelines for metric learning.
- **Custom Loss Functions:** Custom-implemented **Contrastive Loss** and **Triplet Loss** to enforce strict Euclidean distance boundaries between positive and negative pairs in embedding space.
- **Backbone Comparison:** Built and evaluated custom Convolutional Neural Networks (CNNs) against pre-trained transfer learning architectures (**ResNet50**, **MobileNetV2**).
- **Inference & Metrics:** Analyzed Euclidean distance distributions to define optimal distance thresholds and maximize inference accuracy.

---

##  Tech Stack & Tools
- **Framework:** PyTorch
- **Core Libraries:** Torchvision, OpenCV, NumPy, Matplotlib, Scikit-learn
- **Dataset:** Labeled Faces in the Wild (LFW)
- **Language:** Python

---

##  Author
**Mahmoud Ayman Zaki**
- **Email:** mahmoudayman340@gmail.com
- **GitHub:** [@mahmoudayman-22](https://github.com/mahmoudayman-22)
