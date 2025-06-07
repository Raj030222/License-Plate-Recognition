# License-Plate-Recognition
# License Plate Recognition - Data Scientist Intern Assignment

This repository contains my completed assignment for the **Data Scientist Intern position** at **Soulpage IT Solutions Pvt. Ltd.**. The task involves detecting and recognizing vehicle license plates using two annotated datasets.

## 📌 Problem Statement

The primary objectives of this project are:

1. **License Plate Detection** – Detect and localize license plates in vehicle images using bounding box annotations.
2. **Character Recognition** – Accurately recognize and extract alphanumeric characters from cropped license plate images.

---

## 📂 Dataset Overview

The dataset comprises three distinct sets:

- **Training Set 1**: 900 vehicle images with bounding box annotations (`ymin`, `xmin`, `ymax`, `xmax`) identifying license plates.
- **Training Set 2**: 900 cropped license plate images with corresponding alphanumeric text annotations.
- **Test Set**: 201 vehicle images for evaluating both plate detection and character recognition.

> **Note:** Dataset link (provided by the company): [Google Drive Folder](https://drive.google.com/drive/folders/1ThHnUQjkCNTOKXnvySVfpHZxZbYsFfMQ)

---

## 🧠 Approach

### 1. Data Preprocessing
- Converted annotations into structured formats.
- Performed data sanity checks and visualized samples.

### 2. Data Exploration
- Analyzed class distribution, image sizes, and bounding box dimensions.
- Verified label consistency across datasets.

### 3. Model Building

#### 🟡 License Plate Detection:
- Used **YOLOv8** (You Only Look Once) for object detection.
- Trained a custom detection model on Training Set 1.

#### 🔤 Character Recognition:
- Used **CNN (Convolutional Neural Network)** for OCR on plate crops.
- Trained on Training Set 2 to classify alphanumeric characters.

### 4. Evaluation
- Evaluated detection using mAP@0.5.
- Evaluated character recognition using accuracy on test plate texts.

---

## ✅ Results

| Task                  | Model Used | Metric        | Score       |
|-----------------------|------------|---------------|-------------|
| License Plate Detection | YOLOv8      | mAP@0.5       | ~XX% (fill in) |
| Character Recognition   | CNN         | Accuracy      | ~XX% (fill in) |

---

## 📒 Notebook

The complete solution is documented in the `License_Plate_Recognition.ipynb` notebook, including:
- Data loading
- Annotation parsing
- Model training
- Visualizations
- Predictions on test set

---

## 🔧 Tools & Technologies

- Python 🐍
- OpenCV
- TensorFlow / Keras / PyTorch
- YOLOv8 (via `ultralytics`)
- Pandas & NumPy
- Matplotlib & Seaborn

---

## 📧 Contact

  
🌐 Portfolio: [https://raj030222.github.io/raju-portfolio.github.io/](https://raj030222.github.io/raju-portfolio.github.io/)

---

## 📝 License

This repository is submitted as part of an internship assignment and is not for commercial use.
