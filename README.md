# CMPSC488-Capstone: Real-Time License Plate Detection Android App

**Penn State Harrisburg | Senior Capstone Project (2024)**  
**Project Name:** Penn State Plates

## Project Overview

This repository contains the Android application and model integration work for a license plate recognition system. The app uses **YOLOv8** for real-time object detection of license plates via the device camera, followed by **Google ML Kit** for optical character recognition (OCR) to extract plate numbers.

The goal was to replace traditional physical parking passes with a digital solution that reduces waste and simplifies the user experience for students and faculty.

## My Contributions

- Embedded and optimized a **YOLOv8** object detection model into a native **Android** application.
- Built the Android frontend using **Jetpack Compose** and **CameraX** for real-time camera access and preview.
- Implemented the end-to-end pipeline from live camera frames → YOLOv8 inference → bounding box processing → **Google ML Kit Text Recognition** for character extraction.
- Designed and integrated a clean architecture to handle model inference efficiently on-device while maintaining responsive UI performance.
- Collaborated on backend services (FastAPI/Flask) for data handling and Microsoft SQL Server integration.

## Key Technical Achievements

- Successfully integrated YOLOv8 into an Android environment with acceptable real-time performance.
- Built a robust detection → OCR pipeline that processes live camera frames.
- Applied modern Android development practices using Jetpack Compose and CameraX.
- Demonstrated end-to-end computer vision on mobile (detection + recognition) without relying on constant cloud inference.

## Technologies Used

- **Android Development**: Kotlin, Jetpack Compose, CameraX, Gradle (Kotlin DSL)
- **Computer Vision & ML**: YOLOv8 (Ultralytics), Google ML Kit Text Recognition
- **Backend & Data**: FastAPI, Flask, Microsoft SQL Server
- **Tools**: Android Studio, Jupyter Notebooks (for model experimentation)

## Architecture
CameraX → Frame Processing → YOLOv8 Inference→ Bounding Box Extraction → Google ML Kit OCR → Extracted Plate Text 

## Repository Note

This was a **temporary development repository** used primarily for Android model integration and pipeline development. The final consolidated project repository is available here:  
[https://github.com/Seeleysbay/Penn-State-License-Plate-Detection-Capstone](https://github.com/Seeleysbay/Penn-State-License-Plate-Detection-Capstone)

## Team

- Ryan Brennan, Tyler Wallace, **Alan Baxley**, Brendan Gaffney, Jeffrey Tetkoskie  
- Faculty Advisor: Truong Tran

---

**Keywords**: Android, Kotlin, Jetpack Compose, YOLOv8, Computer Vision, OCR, Google ML Kit, CameraX, Mobile ML, Object Detection, License Plate Recognition
