# 🧠 AI, ML, and QML Projects Repository

This repository contains various **Machine Learning (ML)**, **Quantum Machine Learning (QML)**, and **AI** projects that I have worked on during my undergraduate degree.

---

## 📂 Currently Included Projects

### 🔬 Breast Cancer Classification (QNN vs QSVM)
- **Goal**: Binary classification using the Breast Cancer dataset.
- **Models Used**: 
  - Quantum Neural Network (QNN)
  - Quantum Support Vector Machine (QSVM)
- **Approach**: Comparative study of QNN and QSVM performance on the same dataset.

---

### 🧠 Parkinson's Disease Classification (QNN vs QSVM)
- **Goal**: Classify Parkinson's disease using relevant dataset.
- **Models Used**: 
  - Quantum Neural Network (QNN)
  - Quantum Support Vector Machine (QSVM)
- **Approach**: Comparative performance analysis of both models.

---

### 🎨 Color Detection Using OpenCV

This project allows users to detect colors in an image or a webcam stream by clicking on a region of interest. It returns the name and RGB values of the closest matching color from a predefined dataset.

#### ✅ Project Breakdown
- **Stage 1**: Read and display an image using OpenCV.
- **Stage 2**: Detect mouse click events on the image.
- **Stage 3**: Extract RGB values at clicked pixel (converted from BGR).
- **Stage 4**: Match the RGB to known color names using a dataset (`colors.csv`).
- **Stage 5**: Display the matched color name and RGB values on the image.
- **Stage 6 (Optional)**: Enable real-time color detection from webcam feed.

#### 📁 Dataset Used
- **File**: `colors.csv`
- **Columns**:
  - `color_name`
  - `R`, `G`, `B`

#### 📦 Modules Used
- `OpenCV`: For image input/output, mouse handling, and webcam access.
- `Pandas`: For loading and processing the color dataset.

---

## 🔗 Repository Link

You can clone the repository using:
```bash
git clone https://github.com/AdwaithaV/AI-ML.git
