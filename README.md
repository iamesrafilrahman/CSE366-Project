# CSE366-Project

# ☕ Coffee Bean Classifier using Pre-trained CNN (PyTorch)

This repository contains a Jupyter Notebook that demonstrates the use of a **pre-trained Convolutional Neural Network (CNN)** for classifying images of coffee beans using the **Coffee Bean Dataset**. The project utilizes **PyTorch** and **TorchVision**, implementing transfer learning for efficient and accurate classification.

---

## 📁 Dataset

- **Source:** `/kaggle/input/coffee-bean-dataset/Coffee Bean Dataset`
- **Structure:** The dataset contains images categorized into subfolders based on their labels (coffee bean types).

## 🚀 Features

- Uses pre-trained CNN models from `torchvision.models`
- Implements data augmentation with:
  - `RandomResizedCrop`
  - `ColorJitter`
  - `RandomRotation`
  - `GaussianBlur`
- Logs hardware info (CPU, GPU, RAM)
- Includes classification metrics via `sklearn`
- Visualizations of predictions and performance

---

## 🧰 Requirements

Install the necessary libraries:

```bash
pip install torch torchvision torchinfo matplotlib pandas scikit-learn seaborn opencv-python tabulate

🧪 Usage
Clone this repository:

bash
Copy
Edit
git clone https://github.com/yourusername/coffee-bean-cnn.git
cd coffee-bean-cnn

Open the Jupyter Notebook:

bash
Copy
Edit
jupyter notebook pre-trained-cnn7f99696af0.ipynb
Upload the Coffee Bean dataset to the appropriate path (e.g., /input/coffee-bean-dataset/...).

Run each cell to:

Load and preprocess the data

Load a pre-trained CNN model

Train the classifier

Evaluate model performance

Visualize predictions

📊 Results
Model summary using torchinfo.summary

Classification metrics (accuracy, precision, recall, F1-score)

Prediction visualization for sample images

📌 Technologies Used
Python 3

PyTorch

TorchVision

OpenCV

Scikit-learn

Matplotlib & Seaborn

✅ License
This project is licensed under the MIT License. See the LICENSE file for more information.

✍️ Author
Md. Esrafil Rahman
ID: 2020-2-60-106
East-West University, Dhaka, Bangladesh.

