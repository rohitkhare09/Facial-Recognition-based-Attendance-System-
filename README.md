# Facial-Recognition-based-Attendance-System-
This is a Python-based attendance system that uses face recognition to automate attendance marking. Built with a Tkinter GUI, it is user-friendly and suitable for classrooms, offices, and workshops. Faces are detected and recognized using the LBPH (Local Binary Pattern Histogram) algorithm, and attendance is recorded in real-time.

🔹 Features

User-friendly GUI interface for easy operation

Face Recognition for automatic attendance marking

Password-protected registration for new students

Auto-generated daily attendance CSV files with date & time

Real-time attendance display in a tabular format (ID, Name, Date, Time)

Efficient data management using Pandas, NumPy, and CSV

🔹 Technology Stack

Python 3.x

OpenCV – Face detection & recognition (cv2.face.LBPHFaceRecognizer_create())

Tkinter – GUI interface

Pandas / NumPy – Data handling and processing

CSV / datetime – Attendance logging

Pillow – Image processing

🔹 Installation

Clone the repository:

git clone https://github.com/yourusername/face-recognition-attendance.git


Navigate to the project folder:

cd face-recognition-attendance


Install required dependencies:

pip install -r requirements.txt


Requirements include: opencv-contrib-python, numpy, pandas, tkinter, pillow, openpyxl

Run the application:

python main.py

🔹 Usage

Launch the GUI with main.py.

Register new students using the Registration button (password-protected).

Capture student images for the database.

Start the Attendance module to automatically mark attendance via face recognition.

View real-time attendance updates and save records in daily CSV files.

🔹 System Workflow

Image Capture – Capture student images via webcam.

Face Recognition – Detect and recognize faces using the LBPH algorithm.

Attendance Marking – Automatically mark attendance in CSV with date and time.

Real-time Display – Show attendance on GUI in tabular format.

Data Management – Update and maintain student database and attendance logs.

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

🔹 Future Scope

Integration with cloud storage to centralize attendance records

Deployment in real-time classroom environments with multiple camera feeds

Advanced algorithms like CNN-based face recognition for higher accuracy

Mobile app interface for faculty and students

🔹 References

OpenCV Documentation

Pandas Documentation

Ahonen, T., Hadid, A., & Pietikäinen, M. (2006). Face description with local binary patterns: Application to face recognition. IEEE Transactions on PAMI, 28(12), 2037–2041.

🔹 Screenshot
