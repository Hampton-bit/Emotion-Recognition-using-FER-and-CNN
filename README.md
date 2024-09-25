# Facial_Emotion_Recognition
# Emotion Recognition using FER+ and CNN



This project focuses on building a robust emotion recognition system capable of identifying human emotions from facial expressions. Using the **FER+ dataset** and **Convolutional Neural Networks (CNN)**, the model achieves high accuracy through data augmentation and pre-processing techniques.

## Key Features
- **Dataset:** FER+ (Facial Expression Recognition Plus)
- **Architecture:** Convolutional Neural Networks (CNN)
- **Accuracy:** 83.52% validation accuracy
- **Tech Stack:** Python, OpenCV, Keras, TensorFlow

## Project Overview
In this project, I developed an emotion recognition model that can classify facial expressions into distinct emotion categories. The model leverages deep learning techniques, specifically CNNs, and achieves significant performance through the following key components:

- **Pre-processing:** Handled image resizing, normalization, and face detection using OpenCV.
cData Augmentation:** Applied rotation, zoom, and horizontal flip to increase dataset diversity.
- **CNN Architecture:** Built a multi-layer CNN to extract features from images and accurately classify emotions.

## Achievements
- Reached **83.52% validation accuracy** in recognizing facial expressions from the FER+ dataset.
- Successfully implemented a
- **data augmentation pipeline** to enhance model robustness.

## Installation

To run this project locally, follow these steps:

1. **Clone this repository**:
   ```bash
   git clone https://github.com/your-username/emotion-recognition.git
2. **Navigate to the project directory**:
   ```bash
   cd emotion-recognition
3. **Install required dependencies:**:
   ```bash
   pip install -r requirements.txt
## Usage
Once the setup is complete, you can run the model on your own images or the provided dataset. Example commands:

- **Train the model:**
  ```bash
  python train_model.py

 - **Predict emotion from an image:**
   ```bash
   python predict_emotion.py --image_path your_image.jpg
## Future Improvements
- Fine-tune the CNN model for higher accuracy.
- Explore real-time emotion recognition via webcam integration.
