# 🖥️ Face-Based Attendance System using Python & OpenCV

[![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)  
[![Python 3.9](https://img.shields.io/badge/python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/)  

---

## 📌 Overview
The **Face-Based Attendance System** is an AI-powered project that automates the process of recording student attendance using **Facial Recognition Technology**.  
Built with **Python, OpenCV, and Machine Learning**, this system allows seamless attendance marking by identifying and verifying students' faces in real-time.

This is a **group project** developed by **Mihir Kumar** and **Rahul**, where both team members contributed equally to the design, coding, and implementation.

---

## 🚀 Features
- 📷 **Face Registration** — Capture and store multiple images of a student for training.
- 🧠 **Face Training** — Convert captured images into numeric data for recognition.
- ✅ **Automatic Attendance** — Mark attendance in real-time using a webcam.
- 📂 **Attendance Storage** — Save records in `.csv` format per subject.
- 📊 **View Attendance** — Display records in a clean, tabular format.
- 🖥️ **Simple GUI** — User-friendly interface for all actions.

---

## 🛠️ Technologies Used
- **Python 3.9**
- **OpenCV** — For real-time image processing and face detection.
- **face_recognition** library — For facial recognition & verification.
- **dlib** — For deep learning-based facial landmark detection.
- **NumPy** — For numerical computations.
- **Pandas** — For handling attendance data.

---

## 📂 Project Structure
```plaintext
📦 Attendance-System
┣ 📂 TrainingImage               # Stores registered student images
┣ 📂 Project Snap                # Screenshots of the application
┣ 📜 attendance.py               # Main file for GUI and face registration
┣ 📜 automaticAttendance.py      # For real-time attendance marking
┣ 📜 train.py                    # Trains the facial recognition model
┣ 📜 requirements.txt            # Python dependencies
┗ 📜 README.md                   # Documentation
```
---

## 📷 Screenshots

### **Simple User Interface**
<img src="https://github.com/Patelrahul4884/Attendance-Management-system-using-face-recognition/blob/master/Project%20Snap/1.PNG" width="500">

---

### **Face Registration**
![Image](https://github.com/user-attachments/assets/100618fe-44cb-48b6-85e0-e0ab111bfaa8)

---

### **Automatic Attendance**
<img width="1536" height="1024" alt="Image" src="https://github.com/user-attachments/assets/8c38f625-86cc-4398-b935-a0f977746d68" />

---

### **Attendance Table**
<img width="941" height="352" alt="Image" src="https://github.com/user-attachments/assets/0e44cd20-7b5c-486a-b6f6-85329b689899" />

---

## 📖 How to Run the Project

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/MIHIR13396/Attendance-System-using-Facial-Recognition-Technology.git
cd Attendance-System-using-Facial-Recognition-Technology
```
### **1️⃣ Install and Running Commands**
```cmd
- type `pip install -r requirements.txt` in command prompt(this will install required package for project)
- Create a `TrainingImage` folder in a project folder.
- open `attendance.py` and `automaticAttendance.py`, change all the path accoriding to your system
- Run `attandance.py` file
```

### Project flow & explaination
- After you run the project you have to register your face so that system can identify you, so click on register new student
- After you click a small window will pop up in that you have to enter you ID and name and then click on `Take Image` button
- After clicking `Take Image` button A camera window will pop up and it will detect your Face and take upto 50 Images(you can change the number of Image it can take) and stored in the folder named `TrainingImage`. more you give the image to system, the better it will perform while recognising the face.
- Then you have to click on `Train Image` button, It will train the model and convert all the Image into numeric format so that computer can understand. we are training the image so that next time when we will show the same face to the computer it will easily identify the face.
- It will take some time(depends on you system).
- After training model click on `Automatic Attendance` ,you have to enter the subject name and then it can fill attendace by your face using our trained model.
- it will create `.csv` file for every subject you enter and seperate every `.csv` file accoriding the subject
- You can view the attendance after clicking `View Attendance` button. It will show record in tabular format.


