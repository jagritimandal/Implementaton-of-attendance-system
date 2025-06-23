
# Implementation of Student Attendance System using Face Recognition

This project is a **Face Recognition-based Attendance System** designed to automate and streamline the process of recording student attendance using real-time facial recognition.

## 🚀 Features

* 🎓 Detect and recognize student faces in real-time
* 📷 Capture attendance using webcam
* 🕒 Record date and time of attendance
* 💾 Save attendance data to CSV file or database
* 🧠 Train model with student images for recognition
* 📊 Easy-to-use graphical interface (optional, if GUI used)

## 🛠️ Technologies Used

* Python
* OpenCV
* Face Recognition (dlib or face\_recognition library)
* NumPy, Pandas
* Tkinter (if GUI is used)

## 📂 Project Structure

```
student-attendance-system/
├── images/                 # Training images of students
├── attendance/             # Saved attendance CSVs
├── training.py             # Script to encode faces
├── attendance.py           # Main attendance capturing script
├── gui.py                  # Optional: GUI interface
├── utils.py                # Helper functions
├── README.md
```

## 🧑‍🏫 How It Works

1. **Face Registration**
   Add student face images to the `images/` folder. Filenames should match student names.

2. **Training**
   Run `training.py` to generate face encodings for all registered students.

3. **Attendance Capture**
   Run `attendance.py` to launch webcam and mark attendance based on face match.

4. **Storage**
   Attendance records are saved with date and timestamp in CSV format.

## ▶️ Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/student-attendance-system.git
   cd student-attendance-system
   ```

2. Install dependencies:

   ```bash
   pip install opencv-python face_recognition numpy pandas
   ```

3. Add student images to the `images/` folder.

4. Train the model:

   ```bash
   python training.py
   ```

5. Start taking attendance:

   ```bash
   python attendance.py
   ```

## 📌 Future Improvements

* Add GUI with login
* Store data in a database
* Generate attendance reports
* Improve recognition accuracy in low light
