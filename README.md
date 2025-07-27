
# Facial Recognition System using OpenCV

This project implements a real-time facial recognition system using Python and OpenCV. It allows users to detect and recognize human faces from a live video stream using a webcam. The system is capable of storing and recognizing faces based on a pre-built dataset.

##  Features

- Face detection using Haar Cascade classifiers
- Face recognition using LBPH (Local Binary Patterns Histograms) or OpenCV recognizer
- Real-time webcam integration
- Dataset creation using webcam input
- Simple command-line-based interface

## Technologies Used

- Python
- OpenCV
- NumPy
- OS / File I/O


## How It Works

1. **Dataset Creation:**
   - The system captures face images from a webcam and stores them with labels.
   - Each person gets a unique numeric label for training.

2. **Training:**
   - Faces are trained using OpenCV’s face recognizer (LBPH or similar).
   - The trained model is saved to disk.

3. **Recognition:**
   - The webcam captures live video frames.
   - The model detects and recognizes faces in real time.
   - If a face is recognized, the corresponding label or name is displayed.



