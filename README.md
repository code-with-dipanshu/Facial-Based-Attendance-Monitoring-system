
# Face Recognition Based Attendance System

<p align="center">
    <img src="https://upload.wikimedia.org/wikipedia/commons/5/57/OpenCV_Logo.png" alt="Logo" width="200"/>
</p>

## Overview

The **Face Recognition Based Attendance System** is a Python-based application that uses facial recognition to automate the attendance marking process. It utilizes the OpenCV library for face detection and recognition, and Tkinter for building the graphical user interface (GUI). This system allows for student registration, face training, and real-time attendance tracking.

---

### Key Features:

<ul>
    <li>Student Registration: Add new students with ID and Name.</li>
    <li>Face Capture: Capture and store facial images for each student.</li>
    <li>Real-time Attendance Tracking: Mark attendance automatically using facial recognition.</li>
    <li>Password Protection: Secure access to sensitive features with a password.</li>
    <li>Data Storage: Store student data and attendance logs in CSV files for persistence.</li>
</ul>

---

## Project Structure

```
- Attendance/
    - Attendance.csv  (Attendance records for a specific day)
- StudentDetails/
    - StudentDetails.csv  (Stores registered student information)
- TrainingImage/
    - (Folder containing images used for training the face recognition model)
- TrainingImageLabel/
    - Trainer.yml  (Trained model for face recognition)
- haarcascade_frontalface_default.xml  (Haar Cascade Classifier for face detection)
- main.py  (Main Python script to run the system)
- psd.txt  (Password storage file)
```

---

## Installation

### Step 1: Clone the Repository
Clone this repository to your local machine using Git:

```bash
git clone [<your-repo-url>](https://github.com/code-with-dipanshu/Facial-Based-Attendance-Monitoring-system.git)
```

### Step 2: Install Dependencies
This project requires Python and several libraries. Use the following command to install all dependencies:

```bash
pip install -r requirements.txt
```



### Step 3: Run the Application
To run the application, execute the `main.py` script:

```bash
python main.py
```

This will launch the Face Recognition-based Attendance System.

---

## Usage

### 1. Student Registration
In the "New Registration" section, enter a unique ID and Name for the student. Click on the "Take Images" button to capture facial images for the student. Once images are taken, click "Save Profile" to save the student's profile.

### 2. Face Recognition and Attendance Tracking
In the "For Already Registered" section, click the "Take Attendance" button to begin real-time attendance tracking. The system will use the webcam to detect faces and mark attendance automatically. The attendance will be displayed in the table within the application.

### 3. Password Protection
The system is protected with a password for certain functionalities. You can change the password through the "Change Password" option in the menu.

### 4. Viewing Attendance
Attendance records are stored in the Attendance/ folder and can be viewed in CSV format. Each attendance record includes the student's ID, Name, Date, and Time of attendance.

---

## Password Protection

The system uses a password to secure some features. If you are running the system for the first time or need to reset the password:
1. The system will prompt you to enter a new password.
2. Once the password is set, it will be saved in the "TrainingImageLabel/psd.txt" file.
3. Use this password for accessing the "Save Profile" and "Train Images" features.

### Change Password:
To change the password, go to the Help menu and select Change Password. Enter the old and new passwords as prompted.

---

## Contributing

If you wish to contribute to this project, follow these steps:

1. Fork the repository on GitHub.
2. Create a new branch (`git checkout -b feature-name`).
3. Make the desired changes or additions.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push your changes (`git push origin feature-name`).
6. Open a pull request to the main repository.

---

 

## Acknowledgements

<ul>
    <li><strong>OpenCV</strong>: Used for face detection and recognition in this project.</li>
    <li><strong>Tkinter</strong>: Provides the GUI for the application.</li>
    <li><strong>ttkbootstrap</strong>: Enhances the appearance of Tkinter widgets for a modern look.</li>
</ul>

---

## Contact

For any questions or feedback, feel free to reach out at:  
<strong>dipanshumeshram4@gmail.com</strong>
