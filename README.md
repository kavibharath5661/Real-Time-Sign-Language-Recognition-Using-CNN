# Real-Time-Sign-Language-Recognition-Using-CNN

## Description
This project recognizes hand signs in real time using a webcam and deep learning, converting gestures into readable text to help reduce the communication gap for hearing-impaired people. It uses Python with OpenCV, MediaPipe, and TensorFlow to detect hands, extract features, and classify gestures accurately.




## Files
- collect-dataset.py – Collects training data using webcam
- train.py – Trains the deep learning model
- predict.py – Runs real-time prediction
- model.h5 – Trained model file
- labels.npy – Encoded labels

## Installation
```bash
pip install -r requirements.txt
```

## Run Steps
```bash
python collect-dataset.py
python train.py
python predict.py
```

## Notes
- Make sure webcam is working
- Dataset folder should be structured by class names
