# 😷 Face Mask Detection using CNN (Final Year Project)

📍 **University:** The Islamia University of Bahawalpur, Pakistan  
🏛️ **Department:** Information Technology (DIT)  
👩‍💻 **Student:** Laraib Qandeel (Roll No: F22BINFT1E02142)  
👨‍🏫 **Supervisor:** Sir Syed Ali Nawaz Shah  

---

## 🎯 Objective / Scope

The goal of this project is to develop a **Face Mask Detection System** using a **Convolutional Neural Network (CNN)**.  
The system classifies face images into two categories:  
- 😷 **With Mask**  
- 😐 **Without Mask**

### 🔧 Project Workflow
1. 🧠 **Data Collection & Preparation**  
   - Acquire dataset (e.g., from Kaggle).  
   - Resize all images (e.g., 128×128 px) and convert to NumPy arrays.  

2. ⚙️ **Data Splitting & Scaling**  
   - Split dataset into training and testing sets using `train_test_split`.  
   - Normalize pixel values (0–1 range) for model stability.  

3. 🤖 **CNN Model Development & Training**  
   - Build and compile a CNN model using **TensorFlow / Keras**.  
   - Train the model to detect and classify masked vs unmasked faces.  

4. 📊 **Model Evaluation & Prediction**  
   - Evaluate model accuracy on test data.  
   - Use the trained model to predict new, unseen images.

---

## 💻 Tools & Technologies

| Category | Tool / Library | Purpose |
|-----------|----------------|----------|
| 🐍 Programming | **Python** | Core programming language |
| 🔬 Deep Learning | **TensorFlow / Keras** | Build and train CNN model |
| 🧮 Data Handling | **NumPy** | Process image data as arrays |
| 🖼️ Image Processing | **Pillow (PIL)** | Load, resize, and convert images |
| 👁️ Computer Vision | **OpenCV (cv2)** | Image reading and manipulation |
| 🔍 Data Splitting | **Scikit-learn** | Split dataset for training/testing |
| 📈 Visualization | **Matplotlib** | Display and visualize data |
| 🧑‍💻 Development | **Jupyter Notebook** | Interactive coding and model training |

---

## 🚀 Results
- ✅ Successfully trained a CNN model for mask detection.  
- 📉 Model evaluated on test data with high accuracy.  
- 🔍 Can predict real-time mask usage in new images.

---

## 🙌 Acknowledgement
Special thanks to **Sir Syed Ali Nawaz Shah** for guidance and supervision throughout this project.  

---

> 🧾 *This project was developed as part of the Final Year Project (FYP) at The Islamia University of Bahawalpur, Department of Information Technology.*
