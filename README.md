# Face Recognition Attendance System

A face recognition based attendance system using Python, Flask, and OpenCV. This project allows you to mark attendance by capturing images of individuals' faces through a webcam and recognizing them using a machine learning model.

## Features

- Face detection and recognition using Haar cascades and K-Nearest Neighbors algorithm.
- Real-time attendance marking by capturing faces through the webcam.
- User registration to add new users to the attendance system.
- Automatic attendance record generation with date and time stamp.
- Web interface for easy interaction and monitoring of attendance.

## Prerequisites

- Python 3.x
- OpenCV
- Flask
- NumPy
- pandas
- scikit-learn

## Installation

1. Clone the repository:

git clone https://github.com/your-username/face-recognition-attendance.git

css
Copy code

2. Navigate to the project directory:

cd face-recognition-attendance

markdown
Copy code

3. Install the required dependencies:

pip install -r requirements.txt

markdown
Copy code

4. Download the Haar cascade classifier for face detection and place it in the project directory.

5. Run the application:

python app.py

vbnet
Copy code

6. Access the application in your web browser at `http://localhost:5000`.

## Usage

1. Visit the web interface to see the attendance records and the total number of registered users.

2. Click on the "Take Attendance" button to start marking attendance using face recognition.

3. If no trained model is available, you will need to add new users first. Click on the "Add New User" button and follow the instructions to capture images of new users' faces.

4. Once attendance is marked, the system will record the attendance in a CSV file with the date and time.

