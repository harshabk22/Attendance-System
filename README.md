# AI Attendance System

## Overview

The AI Attendance System is a browser-based application that automates attendance tracking using real-time face recognition. It leverages modern web technologies and client-side machine learning to identify individuals and record their attendance without requiring a backend server.

---

## Features

* Face enrollment with name and roll number
* Real-time face detection and recognition using the device camera
* Automatic attendance marking for recognized individuals
* Live dashboard displaying total students and attendance count
* Export of attendance records in CSV format
* Persistent storage using browser local storage

---

## System Workflow

1. The user enrolls a student by capturing their face and entering basic details.
2. The system converts the captured image into a numerical face descriptor.
3. During attendance, the system detects faces in the camera feed.
4. Detected faces are compared against stored descriptors.
5. If a match is found, attendance is recorded with timestamp.

---

## Technology Stack

* Frontend: HTML, CSS, JavaScript
* Face Recognition Library: face-api.js
* Storage: Browser LocalStorage
* Camera Integration: WebRTC (getUserMedia API)



---

2. Open the application:
   Open the file "attendance_web.html" in a modern web browser

3. Grant camera permissions when prompted

4. Use the application:

   * Enroll students
   * Capture face data
   * Mark attendance

---

## Requirements

* A modern web browser (Google Chrome recommended)
* A device with a working camera
* Internet connection to load face recognition models

---

## Limitations

* Data is stored locally and is not shared across devices
* Performance and accuracy depend on lighting and camera quality
* No authentication or user management system


## Author

- Harsha
- Rupesh
---
