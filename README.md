# Handwritten Digit Classification 📷
This notebook demonstrates the use of machine learning algorithms (MLP, Random Forest, SVC, Decision Trees) to classify handwritten digit images. It covers dataset preprocessing, feature extraction, model training, and evaluation to optimize accuracy in digit recognition tasks.

## 📝 Project Overview
This project leverages machine learning techniques to classify handwritten digit images. The goal is to train models that can accurately identify digits (0-9) from images, making this project ideal for understanding image classification and preprocessing techniques. Various machine learning models are applied, including MLP, Random Forest, SVC, and Decision Trees, with hyperparameter tuning to improve accuracy.

Handwritten digit recognition is a fundamental problem in machine learning, used in areas like postal services, document scanning, and automated data entry.

## 📂 Dataset
The dataset consists of images of handwritten digits (0-9), each image is a 10x10 pixel grayscale image. The labels represent the corresponding digits.

| Column Name            | Description |
|------------------------|-------------|
| `Image`                 | 	Flattened pixel values of the image |
| `Label`            | 	The target digit (0-9) for each image |

## 🔄 Data Processing Workflow

### 1️⃣ **Dataset Preparation**
- Downloading the dataset and extracting images.
- Storing image paths and labels in a structured format for easy access.

### 2️⃣ Image Preprocessing
- Converting images to grayscale and resizing to 10x10 pixels.
- Flattening images into a 1D array to make them suitable for machine learning models.

### 3️⃣ **Model Development & Training**
- We applied four different machine learning models to classify the handwritten digits:
  - MLP (Multi-Layer Perceptron)
  - Random Forest Classifier
  - Support Vector Classifier (SVC)
  - Decision Tree Classifier
 
### 4️⃣ **Model Evaluation**
- Models were evaluated using:
  - Accuracy
  - Precision
  - Recall
- Hyperparameters were tuned using RandomizedSearchCV for optimal performance.

## 🚀 How to Run the Project

### **1️⃣ Clone the Repository**
- Clone this repository to your local machine:
```sh
$ git clone https://github.com/yourusername/Handwritten-Digit-Classification.git
$ cd Handwritten-Digit-Classification
```

### **2️⃣ Install Dependencies**
- Make sure all required libraries are installed:
```sh
$ pip install -r requirements.txt
```

### **3️⃣ Run the Jupyter Notebook**
- Start the Jupyter Notebook to explore and run the project:
```sh
$ jupyter notebook
```
Open Handwritten_Digit_Classification.ipynb and execute the cells.

## 📊 Results & Insights

### 🏆 Best-Performing Model
- MLP achieved the highest accuracy, showcasing its ability to handle complex patterns in image data.

### ⚡ Other Models:
- Random Forest: Almost matched MLP, performing well with slight improvements possible through hyperparameter tuning.
- SVC: Showed promising results but can be optimized further by adjusting the kernel and feature scaling.
- Decision Tree: Performed poorly due to overfitting, showing the limitations of simpler models in complex tasks.

## 🚀 Future Enhancements
- 🔹 Experiment with Convolutional Neural Networks (CNNs) to leverage their strength in image recognition tasks.
- 🔹 Implement data augmentation to increase model robustness and diversity.
- 🔹 Tune the SVC kernel and explore more advanced tuning techniques to improve model performance.

## 🔚 Conclusion
This project demonstrates how various machine learning models can be applied to solve the handwritten digit classification problem. By experimenting with different algorithms, we were able to identify the most suitable model for this task. Future improvements will focus on using deep learning and other advanced techniques to enhance the model’s performance further.

