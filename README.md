# Number Plate Recognition

## Overview
This project implements a **Number Plate Recognition** system using **OpenCV** and Haar Cascade classifiers. The system captures video from a webcam, detects number plates in real-time, and allows the user to save detected plates as images.

## Key Features
- **Real-time Detection**: Utilizes webcam input to detect number plates in real-time.
- **Image Processing**: Draws bounding boxes around detected number plates and displays them.
- **Image Saving**: Allows users to save detected number plates as images by pressing a key.

## Technologies Used
- **OpenCV**: For image processing and computer vision tasks.
- **Haar Cascade Classifier**: For number plate detection.

## Getting Started

### Prerequisites
Make sure you have the following installed:
- Python 3.x
- OpenCV library

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/number_plate_recognition.git
   cd number_plate_recognition
   
2. Install the required dependencies:
   ```bash
   pip install opencv-python

3. Download the Haar Cascade XML file for number plate detection and place it in the project directory. You can find pre-trained Haar Cascade models online.

### Usage
1. Open the script: app.py

2. Run the script:
   ```bash
   python number_plate_recognition.py

3. Press the 's' key to save the detected number plate image.

## Output Example
When a number plate is detected, a rectangle will be drawn around it, and a message indicating that the plate has been saved will be displayed on the screen. The saved images will be stored in the "plates" directory.

## Datasets
This model does not require a specific dataset, as it uses a pre-trained Haar Cascade classifier for number plate detection.

## Google Drive Link for this project
https://drive.google.com/file/d/1JcXW9Vses3GX1EpFBFum5XZ3p5REwEQF/view

