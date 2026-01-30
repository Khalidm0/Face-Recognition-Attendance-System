# Face Recognition Attendance System
(Human–Computer Interaction Project)

## Overview
The Face Recognition Attendance System is a desktop-based application developed as part of a Human–Computer Interaction (HCI) course. The system automates attendance tracking using real-time face recognition while focusing on usability, responsiveness, and efficient interaction design.

The application provides an intuitive graphical user interface that enables instructors to manage lectures, train face data offline, and record attendance accurately without manual effort.

## Project Objectives
- Automate attendance using face recognition
- Apply HCI principles such as usability, feedback, and error prevention
- Design a responsive and non-blocking GUI
- Reduce instructor effort and cognitive load

## Features
- Offline face dataset training
- Real-time multi-face recognition
- Automatic attendance marking
- Instructor and lecture management
- Attendance report generation (CSV and PDF)
- Thread-safe GUI (no freezing during processing)

## HCI Focus
- Simple and consistent interface design
- Clear system feedback and status indicators
- Logical and efficient task flow
- Responsive interaction using multithreading
- Minimal user input for common tasks

## Technologies Used
- Python 3.10
- Tkinter (GUI)
- OpenCV
- face_recognition (dlib)
- MySQL (XAMPP)
- FPDF

## System Requirements
- Python 3.10.x
- Webcam
- MySQL (XAMPP)

Note: Newer Python versions (3.13 / 3.14) are not supported due to dlib compatibility issues.

## How to Run
1. Start MySQL using XAMPP
2. Create the database named `attendance_system`
3. Run the face training script
4. Run the main application
5. Start an attendance session
6. Generate attendance reports

## Output
- Attendance records stored in MySQL database
- Exportable attendance reports in CSV and PDF formats

## Project Status
Completed, tested, and ready for academic submission.
