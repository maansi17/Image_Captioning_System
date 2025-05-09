#  Image_Captioning_System — VGG16 & DenseNet121 Based Models

**Automated Image Captioning and Detailed Description System (VGG16 & DenseNet121)**

This project implements a deep learning-based system to automatically generate captions for images. It uses pre-trained convolutional neural networks **VGG16** and **DenseNet121** for feature extraction, and a decoder built using **LSTM** combined with an **attention mechanism** to produce human-like descriptions. A **graphical user interface (GUI)** enables real-time comparison of the two models on uploaded images.

---

##  Project Highlights

-  **CNN-based Feature Extraction** using VGG16 and DenseNet121
-  **LSTM Decoder** for generating sequential word-based captions
-  **Attention Mechanism** to focus on relevant image regions
-  Evaluated using **BLEU-1** and **BLEU-2** scores
-  **GUI Interface** built with Tkinter for interactive testing and comparison

---

##  Dataset

**Flickr_8k Dataset**
- 8,000+ images
- 5 human-written captions per image
- Contains a diverse range of scenes, objects, and actions

---

##  Technologies Used

- Python 3.x
- TensorFlow / Keras
- VGG16, DenseNet121 (pre-trained on ImageNet)
- LSTM, Attention Mechanism
- Tkinter (for GUI)
- Numpy, Matplotlib, PIL

---

## BLEU Score Comparison

| Model       | BLEU-1     | BLEU-2     |
|-------------|------------|------------|
| VGG16       | 0.425028   | 0.253021   |
| DenseNet121 | 0.519030   | 0.299039   |

