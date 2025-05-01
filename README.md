✨ Face Recognition Based Attendance Monitoring System ✨

🚀 PROJECT OVERVIEW

Face Recognition Based Attendance Monitoring System is an AI-powered solution that automates attendance marking in real time using computer vision. Leveraging OpenCV’s Haar Cascade classifier for detection and a robust face recognition model for identification, this system replaces manual roll calls, improves accuracy, and saves valuable time for educational institutions and organizations.

🧰 TECH STACK

Programming Language: Python 3.8+

Computer Vision: OpenCV

Face Detection: Haar Cascade Classifier

Face Recognition: face_recognition library (based on dlib)

Database & Storage: SQLite / CSV

GUI (Optional): Tkinter or PyQt5

Environment Management: virtualenv or conda

📦 FEATURES & HIGHLIGHTS

🎥 Real-Time Face Detection: Uses Haar Cascades for fast and accurate face localization.

🏷️ Face Recognition: Matches live faces against a trained dataset for identity verification.

⏰ Automated Attendance Logging: Records timestamped attendance entries, avoiding duplicates per session.

📊 Data Persistence: Stores logs in SQLite or exports to CSV/Excel for seamless reporting.

🛠️ Configurable Dataset: Easily add new users by capturing multiple training images.

🖥️ User Interface: Simple CLI or GUI launcher for end-users.

🔒 Security & Privacy: Local storage of images and logs; no third-party data sharing.


🎯 USAGE

Register New Users: Add face images to dataset/<Name>/.

Re-train Model: python train_model.py after adding new users.

Start Recognition: Launch recognize_and_mark.py to begin real-time attendance.

View Logs: Open attendance.csv or query the SQLite database.


🔍 DEMO & SCREENSHOTS

<img width="960" alt="Screenshot 2025-05-01 200024" src="https://github.com/user-attachments/assets/f7900cea-fcde-4ca8-98be-dde32665f185" />



