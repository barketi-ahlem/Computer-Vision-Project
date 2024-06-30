# 📸 Smart-attendance-system-based-on-face-detection-and-recognition 📸

An end-to-end machine learning project tailored for implementing an intelligent attendance system leveraging state-of-the-art face detection and recognition techniques.

## 🔍 Project Workflow:

### 1. **Feature Engineering**: 
We kick off by enhancing the dataset. The Histogram of Oriented Gradients (HOG) features are extracted utilizing the Scikit-Image library to lay the groundwork for efficient face detection.

### 2. **Binary Classification using Scikit-Learn**: 
- **Data Partitioning**: The dataset is bifurcated into training and test sets to facilitate model evaluation.
- **Model Training**: Various binary classifiers are trained. We adopt the best estimator for each to ensure optimal face recognition.

### 3. **Evaluating the Best Face Detector**: 
A thorough assessment of the trained face detector's efficiency and accuracy is carried out to ensure real-world applicability.

### 4. **Finding Faces in New Images**: 
Utilizing a sliding window approach, we scan new images to detect and evaluate each potential face patch. This aids in real-time attendance marking.

---

👥 Dive into the future of attendance systems, making manual roll calls a thing of the past! 👥
