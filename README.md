AttendEase - Smart Attendance Management System

AttendEase is a facial recognition-based attendance management system built with Python and OpenCV.
It automates the attendance tracking process by capturing, training, and recognizing faces in real-time.

🚀 Tech Stack

Python 3.x

OpenCV – Image processing and facial recognition

NumPy – Numerical computations

PIL (Python Imaging Library) – Image handling

Threading – Concurrent operations

LBPH Face Recognizer – Face recognition algorithm

✨ Features

📷 Camera testing functionality

👤 Face capture and registration

🧠 Face recognition training

✅ Automated attendance marking

📊 CSV-based attendance records

⚡ Real-time face detection

📂 Project Structure
AttendEase/
├── Attendance/              # Stores attendance records
├── StudentDetails/          # Contains student information
├── TrainingImage/           # Stores captured face images
├── TrainingImageLabel/      # Contains trained model data
├── capture_image.py         # Image capture module
├── check_camera.py          # Camera testing module
├── recognize.py             # Face recognition module
├── train_image.py           # Model training module
└── main.py                  # Main application entry point

⚙️ Installation

Clone the repository or download the ZIP file:

Install the required dependencies:

pip install opencv-python
pip install numpy
pip install pillow

▶️ How to Use

Run the main application:

python main.py


Choose from the following options:

Test Camera: Verify camera functionality

Capture Faces: Register new students/employees

Train Images: Train the system with captured faces

Recognize & Attendance: Start attendance marking

Attendance records are automatically saved in CSV format inside the Attendance/ folder.

📋 Requirements

Python 3.x

Webcam

Minimum 512MB RAM

At least 1GB free disk space

📌 Future Improvements

Enhance accuracy with deep learning models (CNN-based recognition).

Add a web dashboard for viewing attendance reports.

Support cloud storage for attendance data.
