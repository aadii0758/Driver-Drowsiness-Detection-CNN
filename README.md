Driver Drowsiness Detection using CNN

Project Overview

Driver Drowsiness Detection is a computer vision and deep learning project that detects whether a driver is feeling sleepy by monitoring their eye movements.

The system uses a Convolutional Neural Network (CNN) to classify eyes as Open or Closed. If the driver's eyes remain closed for a certain duration, the system triggers an alarm to alert the driver.

The main objective of this project is to help reduce road accidents caused by driver fatigue and drowsiness.

Technologies Used

- Python
- TensorFlow / Keras
- OpenCV
- NumPy
- Pandas
- Convolutional Neural Network (CNN)
- Jupyter Notebook

Features

- Real-time face and eye detection
- Open and Closed eye classification
- CNN-based prediction
- Drowsiness detection
- Alarm alert system
- Visual warning message

Project Structure

Driver-Drowsiness-Detection-CNN/
│
├── app.py
├── detect_drowsiness.py
├── drowsness_new.h5
├── README.md
└── requirements.txt

Note: The actual files may vary depending on the project version.

Installation

1. Clone the Repository

git clone https://github.com/aadii0758/Driver-Drowsiness-Detection-CNN.git

2. Navigate to Project Folder

cd Driver-Drowsiness-Detection-CNN

3. Install Dependencies

pip install -r requirements.txt

Dataset

The dataset contains images of:

1. Closed Eyes
2. Open Eyes
3. Yawn
4. No Yawn

Dataset Reference:

https://www.kaggle.com/datasets/dheerajperumandla/drowsiness-dataset

CNN Model

The project uses a Convolutional Neural Network (CNN) trained to classify eye images into open and closed categories.

Model Performance

The original project reports:

- Training Accuracy: 98%
- Validation Accuracy: 96%
- Training Epochs: 50

These are the reported results from the original project and may vary when retrained.

How It Works

1. The webcam captures live video.
2. OpenCV processes the video frames.
3. The system detects the driver's eyes.
4. CNN predicts whether the eyes are open or closed.
5. If the eyes remain closed for a specified duration, an alarm is triggered.

Future Improvements

- Improve prediction accuracy.
- Add fatigue detection using facial landmarks.
- Develop a web-based interface.
- Add real-time monitoring and alerts.

Author

Aman Kumar

License

This project is intended for educational and research purposes.