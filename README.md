# Week-3
DriveAware is a real-time driver drowsiness detection system that uses facial landmarks and Eye Aspect Ratio (EAR) to monitor eye closure. When drowsiness is detected, the system displays an alert and triggers an alarm, helping prevent accidents caused by driver fatigue.

## Week-3 Improvements
- Completed full project structuring with separate folders for models, reports, and assets.
- Added a detailed README with setup instructions and environment configuration.
- Integrated Google Drive link for the Dlib model file due to GitHub file size limits.
- Refined code structure for better readability and stability.
- Enhanced documentation for final project submission.

## Project Structure
DriveAware/
├── main.py
├── music.wav
├── models/
│ ├── README.txt
│ └── shape_predictor_68_face_landmarks.dat (download separately)
├── requirements.txt
└── reports/


## Model File (Required)
Download the Dlib model file from the link below and place it in the `models` folder:

https://drive.google.com/file/d/1_As0iQkvQtG-thenuPW3oVI1_e0bb1gJ/view?usp=drive_link

## Installation
Install the required packages:


## How to Run
Run the application:

Press **q** to close the program.

## Output
- Displays real-time webcam feed with eye detection  
- Draws eye contours  
- Shows ALERT message when drowsiness is detected  
- Plays an alarm sound
