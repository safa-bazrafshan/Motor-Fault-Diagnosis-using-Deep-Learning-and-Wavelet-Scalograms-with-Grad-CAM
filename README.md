# 🛠️ Motor Fault Diagnosis using Deep Learning and Wavelet Scalograms

This project presents a deep learning-based approach for diagnosing faults in electric motors using synthetic signal data, wavelet-based scalograms, and CNN classifiers with Grad-CAM explainability.

---

## 📌 Overview

Electric motor faults such as bearing damage or broken rotors can be catastrophic in industrial systems. This project simulates such faults, transforms them into scalogram images using Continuous Wavelet Transform (CWT), and trains a Convolutional Neural Network (CNN) to classify the signals into three categories:

- ✅ Healthy  
- ❌ Broken Rotor  
- ⚠️ Bearing Fault

---

## 📈 Key Features

- Synthetic data generation for motor conditions  
- Feature extraction via Wavelet Scalograms (CWT)  
- CNN training and evaluation  
- Model comparison with SVM, KNN, and Decision Tree  
- Visual explainability using Grad-CAM

---

## 🔍 Grad-CAM Heatmaps

Grad-CAM highlights the areas of the image the model focuses on while making predictions:

![Grad-CAM Example](./gradcam_bearing_fault_1.png)

---

## 🧠 Classifier Performance

| Classifier      | Accuracy (%) |
|-----------------|---------------|
| CNN (DNN)       | 71.67%        |
| SVM             | 100.00%       |
| KNN             | 100.00%       |
| Decision Tree   | 94.44%        |

---

## 🗂️ Project Structure

├── data/                         # Synthetic signal and scalogram data ├── spectrograms/                # CWT images ├── gradcam/                     # Grad-CAM visualizations ├── models/                      # Trained model (optional) ├── scripts/ │   ├── generate_data.py │   ├── create_scalograms.py │   ├── train_cnn.py │   ├── evaluate_models.py │   └── gradcam_visualize.py ├── README.md

---

## 🚀 How to Run

1. Clone this repository  
2. Install requirements:

pip install -r requirements.txt

3. Run training and evaluation scripts  
4. View results and Grad-CAM visualizations

---

## 📄 License

MIT License

---

## 🙋‍♀️ Author

Safa Bazrafshan  
Email: safa.bazrafshan@gmail.com

---

⭐️ If you find this useful, feel free to star the repo and connect with me on [https://www.linkedin.com/in/safa-bazrafshan-04100a29a/]
