# Image Classification Using Machine Learning & Deep Learning AICTE Internship

I have done this project to classify images by using CNNmodel and Pre Trained Mobile Net model. I created the streamlit app for the same.
This repository contains a project that demonstrates image classification using machine learning (ML) and deep learning techniques. It includes two models: MobileNetV2 (pre-trained on ImageNet) and a custom CIFAR-10 model trained for classifying images into 10 categories. The project is designed for educational purposes and serves as an excellent example for beginners and enthusiasts exploring ML and DL concepts.

## Features

### MobileNetV2 (Pre-trained on ImageNet):
- Classifies general images into one of 1,000 categories using the **MobileNetV2** architecture.
- Utilizes a pre-trained model to demonstrate the power of **transfer learning**.
- Requires minimal computational resources while delivering robust performance.

### CIFAR-10 Custom Model:
- Classifies images into one of 10 categories: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.
- Includes a lightweight **CNN model** trained on the CIFAR-10 dataset for educational purposes.
- Demonstrates **preprocessing**, **training**, and **prediction** on a popular dataset.

## Key Highlights

### Streamlit Web Application:
- A user-friendly interface that allows users to upload images and view predictions.
- Interactive navigation between the **MobileNetV2** and **CIFAR-10** models.

### Real-time Predictions:
- Upload any image and get **classification results** instantly.
- Predictions displayed with **confidence percentages**, providing transparency into the model's decision-making.

## Getting Started

### Prerequisites

- Python 3.7 or later
- A web browser

### Installation

1. **Clone the repository:**
   
Bash
git clone https://github.com/NIDHISH123/Image-Classification-Using-Machine-Learning-Deep-Learning-AICTE-Internship
Use code with caution.

Create and Activate a Virtual Environment (Recommended):

2. **Linux/macOS:**

Bash
python -m venv venv
source venv/bin/activate  # Activate the virtual environment
Use code with caution.

3. **Install the required packages:**

Bash
pip install -r requirements.txt
Use code with caution.

4. **Start the Streamlit app:**

Bash
streamlit run Myapp.py
Use code with caution.

5. **Open Your Web Browser:**

The app will open in your default web browser. If not, navigate to http://localhost:8501

### Usage
1. Use the navigation bar to select either the MobileNetV2 or CIFAR-10 model.
2. Upload an image file (JPG or PNG).
3.View the classification results and confidence scores.

### Contributing
Feel free to fork the repository, open issues, or submit pull requests to contribute to the project.

### Ack

Streamlit
TensorFlow
