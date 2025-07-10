# Traffic-signal-recognition

This project focuses on building a machine learning model to accurately recognize and classify traffic signs from static images. Our work contributes to safer autonomous vehicle systems by enhancing real-time traffic sign detection.

---
🚗 Problem Statement
--
With the rise of autonomous vehicles, recognizing and interpreting road signs is essential for safety and legal compliance. Our objective is to train a machine learning model to accurately identify 43 different types of traffic signs using image data.

📂 Dataset
--
Source: GTSRB - German Traffic Sign Dataset

Classes: 43

Image Size: 32x32

🛠 Tools & Libraries
--
scikit-learn, OpenCV, NumPy, skimage, matplotlib, pickle

🔍 Method Summary
--
Grayscale conversion & edge detection (Prewitt)

Resizing, normalization, and data augmentation

Trained models: Random Forest, SVM, KNN, Naive Bayes

Best model: Random Forest – 90% accuracy

🧠 Future Work
--
Try CNNs for better real-time accuracy

Expand dataset & integrate into video applications
