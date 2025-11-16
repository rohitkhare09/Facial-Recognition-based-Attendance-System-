# Facial-Recognition-based-Attendance-System
This is a Python-based attendance system that uses face recognition to automate attendance marking. Built with a Tkinter GUI, it is user-friendly and suitable for classrooms, offices, and workshops. Faces are detected and recognized using the LBPH (Local Binary Pattern Histogram) algorithm, and attendance is recorded in real-time.

🔹 Features

-User-friendly GUI interface for easy operation

-Face Recognition for automatic attendance marking

-Password-protected registration for new students

-Auto-generated daily attendance CSV files with date & time

-Real-time attendance display in a tabular format (ID, Name, Date, Time)

-Efficient data management using Pandas, NumPy, and CSV

🔹 Technology Stack

-Python 3.x

-OpenCV – Face detection & recognition (cv2.face.LBPHFaceRecognizer_create())

-Tkinter – GUI interface

-Pandas / NumPy – Data handling and processing

-CSV / datetime – Attendance logging

-Pillow – Image processing

🔹 Usage

-Launch the GUI with main.py.

-Register new students using the Registration button (password-protected).

-Capture student images for the database.

-Start the Attendance module to automatically mark attendance via face recognition.

-View real-time attendance updates and save records in daily CSV files.

🔹 System Workflow

-Image Capture – Capture student images via webcam.

-Face Recognition – Detect and recognize faces using the LBPH algorithm.

-Attendance Marking – Automatically mark attendance in CSV with date and time.

-Real-time Display – Show attendance on GUI in tabular format.

-Data Management – Update and maintain student database and attendance logs.

🔹 Project Structure
face-recognition-attendance/
│
├─ images/                  # Stored student images
├─ attendance/              # Auto-generated attendance CSV files
├─ main.py                  # Main program to run GUI
├─ register.py              # Registration module
├─ recognize.py             # Face recognition & attendance module
├─ requirements.txt         # Required Python libraries
└─ README.md                # Project documentation

🔹 References

-OpenCV Documentation

-Pandas Documentation

🔹 Screenshot
https://github.com/rohitkhare09/Facial-Recognition-based-Attendance-System-/blob/1d20c2101453058b821538f56e65e91a874d162e/Screenshot.png
