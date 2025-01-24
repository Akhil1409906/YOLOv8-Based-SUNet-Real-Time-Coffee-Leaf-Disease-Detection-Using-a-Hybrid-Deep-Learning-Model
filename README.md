# YOLOv8-Based SUNet: Coffee Leaf Disease Detection Using a Hybrid Deep Learning Model

This project introduces a hybrid deep learning model using YOLOv8 and SUNet to detect and classify diseases on coffee leaves. The model is trained to identify common coffee plant diseases, including Brown Eye, Leaf Rust, Leaf Miner, and Red Spider Mite, enabling real-time detection with high accuracy. YOLOv8’s advanced object detection capabilities allow for fast and accurate classification, making it suitable for on-field deployment through mobile devices or drones.

## Problem Statement

Coffee plants are susceptible to various diseases, which can lead to significant yield loss and quality degradation. Timely and accurate detection is crucial for early intervention to minimize crop losses. This project aims to create an efficient solution for detecting diseases on coffee leaves by leveraging state-of-the-art deep learning models.

## Features

- **Real-time Disease Detection**: The model can process images of coffee leaves in real time, identifying diseases such as Brown Eye, Leaf Rust, Leaf Miner, and Red Spider Mite.
- **High Accuracy and Speed**: By using YOLOv8, known for its efficiency in object detection, this model ensures quick and accurate detection, essential for field use.
- **Lightweight and Scalable**: YOLOv8’s architecture is lightweight enough for deployment on mobile devices or drones, making it an ideal solution for on-field deployment.
- **Custom Dataset**: The model is trained on a custom dataset consisting of a variety of coffee leaf images, ensuring robust performance under different environmental conditions.
- **Practical Application**: The model can aid farmers in the timely identification and treatment of affected plants, improving coffee production quality and reducing the need for excessive pesticide use.

## Technologies Used

- **YOLOv8**: Advanced object detection model that ensures real-time and high-accuracy detection.
- **Python**: Programming language used for training and model development.
- **TensorFlow/Keras**: Deep learning frameworks used for building and training the model.
- **OpenCV**: Used for image processing and visualizations.
- **CUDA**: For utilizing GPU acceleration during model training and inference.

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/Akhil1409906/coffee-leaf-disease-detection.git

2. Navigate to the project directory:
    cd coffee-leaf-disease-detection
   
4. Create a virtual environment (recommended):
   python -m venv venv
source venv/bin/activate  # For Linux/macOS
.\venv\Scripts\activate  # For Windows

5. Install the required dependencies:
    pip install -r requirements.txt

