# SCT_ML_03
Built a Support Vector Machine (SVM) model to classify cat and dog images using the Kaggle Dogs vs Cats dataset. The project includes image preprocessing, resizing, normalization, model training, evaluation with accuracy, confusion matrix, and prediction visualization using Python and Scikit-learn.
# 🐱🐶 Cats vs Dogs Image Classification using Support Vector Machine (SVM)

A Machine Learning project that classifies images of **Cats** and **Dogs** using a **Support Vector Machine (SVM)** classifier. This project demonstrates the complete machine learning workflow, including image preprocessing, feature extraction, model training, evaluation, and prediction visualization using the Kaggle Dogs vs Cats dataset.

---

## 📌 Project Overview

The goal of this project is to build an image classification model capable of distinguishing between cats and dogs. Images are preprocessed by resizing, normalizing, and flattening them into feature vectors before training an SVM classifier. The trained model is evaluated using standard performance metrics and visualized with prediction results and a confusion matrix.

---

## 🚀 Features

* Image preprocessing (resize, RGB conversion, normalization)
* Feature extraction using flattened image pixels
* Training and testing using Support Vector Machine (SVM)
* Performance evaluation with:

  * Accuracy Score
  * Classification Report
  * Confusion Matrix
* Visualization of predictions with actual and predicted labels
* Color-coded prediction results (Green = Correct, Red = Incorrect)

---

## 📂 Dataset

**Dataset:** Dogs vs Cats

Dataset Structure:

```text
dogs-vs-cats/
│
├── training_set/
│   └── training_set/
│       ├── cats/
│       └── dogs/
│
└── test_set/
    └── test_set/
        ├── cats/
        └── dogs/
```

---

## 🛠️ Technologies Used

* Python
* Google Colab
* NumPy
* OpenCV
* Matplotlib
* Scikit-learn

---

## 📚 Libraries Used

```python
numpy
opencv-python
matplotlib
scikit-learn
os
zipfile
```

Install dependencies:

```bash
pip install numpy opencv-python matplotlib scikit-learn
```

---

## 🔄 Project Workflow

```text
Dataset
   │
   ▼
Load Images
   │
   ▼
Resize Images (64×64)
   │
   ▼
Convert to RGB
   │
   ▼
Normalize Pixel Values
   │
   ▼
Flatten Images
   │
   ▼
Train-Test Split
   │
   ▼
Train SVM Classifier
   │
   ▼
Prediction
   │
   ▼
Model Evaluation
   │
   ├── Accuracy
   ├── Classification Report
   └── Confusion Matrix
   │
   ▼
Prediction Visualization
```

---

## 📊 Model Evaluation

The model performance is evaluated using:

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

Example:

```text
Training Accuracy : XX%

Testing Accuracy : XX%
```

The project also visualizes:

* Correct Predictions (Green)
* Incorrect Predictions (Red)

---

## 📈 Results

The SVM classifier successfully classifies cat and dog images after preprocessing.

Evaluation includes:

* ✔️ Training Accuracy
* ✔️ Testing Accuracy
* ✔️ Classification Report
* ✔️ Confusion Matrix
* ✔️ Prediction Visualization

---

## 📷 Sample Output

The notebook displays:

* Sample test images
* Actual Labels
* Predicted Labels
* Green titles for correct predictions
* Red titles for incorrect predictions

---

## 📁 Project Structure

```text
Cats-vs-Dogs-SVM/
│
├── Cats_Dogs_SVM.ipynb
├── README.md
├── requirements.txt
├── training_set/
├── test_set/
└── images/
```

---

## ▶️ How to Run

1. Clone the repository.

```bash
git clone https://github.com/your-username/Cats-vs-Dogs-SVM.git
```

2. Navigate to the project folder.

```bash
cd Cats-vs-Dogs-SVM
```

3. Install the required libraries.

```bash
pip install -r requirements.txt
```

4. Open the notebook in Google Colab or Jupyter Notebook.

5. Upload or extract the dataset.

6. Run all cells sequentially.

---

## 📌 Future Improvements

* Extract HOG (Histogram of Oriented Gradients) features before training.
* Apply PCA for dimensionality reduction.
* Perform hyperparameter tuning using GridSearchCV.
* Compare Linear and RBF SVM kernels.
* Use deep learning feature extraction (CNN embeddings) with SVM for improved accuracy.

---

## 🎯 Learning Outcomes

Through this project, I learned:

* Image preprocessing techniques
* Feature extraction for image classification
* Working with Support Vector Machines (SVM)
* Model evaluation using machine learning metrics
* Data visualization using Matplotlib
* Building an end-to-end image classification pipeline

---

## 📜 Internship Task

This project was completed as part of the **SkillCraft Technology Machine Learning Internship (Task 2)**.

**Task:** Implement a Support Vector Machine (SVM) to classify images of cats and dogs using the Kaggle dataset.

---

## 🤝 Connect With Me

**GitHub:** [https://github.com/harika-1296](https://github.com/harika-1296)

**LinkedIn:** *https://www.linkedin.com/in/gundla-harika-reddy-613111332/*

---

## ⭐ If you found this project helpful, please consider giving it a star on GitHub!
