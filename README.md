# -Plant-Disease-Detection-using-Hybrid-AI-CNN-SVM-CNN-Random-Forest-
This mini project presents a hybrid AI-based system for classifying **Capsicum (Bell Pepper) leaf diseases** using a combination of **Convolutional Neural Networks (CNN)** for feature extraction and **Support Vector Machine (SVM)** and **Random Forest (RF)** for final classification.
It is designed to run entirely on a **local machine**, with no web/mobile interface. The project is implemented in a single `.py` script and includes a detailed PDF report.

---

## 📁 Project Files

- `plant_disease_detector.py` – Main Python script that:
  - Loads & preprocesses an image
  - Extracts features using CNN
  - Classifies using SVM and Random Forest
  - Displays prediction and recommendation

- `Plant_Disease_Detection_Report.pdf` – Final project documentation

---

## 🧠 Technologies Used

- Python 3.x  
- TensorFlow & Keras (for CNN-based feature extraction)  
- Scikit-learn (for SVM & Random Forest classification)  
- OpenCV (for image preprocessing)  
- NumPy (array handling)  
- Matplotlib (to display output image & plots)

---

## 🖼️ Dataset

- Source: Kaggle (Pepper Bell Crop DS)
   - https://www.kaggle.com/code/jamijubaer/pepper-bell-disease-classification
  
- Categories:
  - Healthy Leaf Images (1477 samples)
  - Bacterial Spot Diseased Leaves (997 samples)
- Format: `.JPG`
- Dataset was pre-split into training, validation, and test sets

---

## 🚀 How to Run

1. Clone or download the repository

2. Install required libraries:
   ```bash
   pip install tensorflow scikit-learn opencv-python numpy matplotlib
    ```
3. Run the script:
   python plant_disease_detector.py
   
5. The script will:

Load a test image (update path if needed)

Preprocess the image

Extract features using CNN

Predict using both SVM and Random Forest

Print predictions and display the input image
## 📊 Results Summary

## 💬 Prediction Output Example
SVM Prediction: Healthy
Random Forest Prediction: Healthy

🌱 Farmer Recommendation:
The bell pepper plant leaf is healthy. Continue maintaining good agricultural practices.
## 📄 Report
For a complete explanation of methodology, dataset, model comparison, and results, refer to:

📘 Plant_Disease_Detection_Report.pdf


## ✨ Future Scope
Support for more crop diseases

Integration with mobile or IoT devices

Transfer learning with pre-trained CNN models (e.g., VGG16, ResNet)

## 👨‍💻 Developed By
Hanith CG and Team
Mini Project – B.Tech AI & Data Science
hanithcg@gmail.com


