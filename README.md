### 🤖 PIV - Computer Vision Projects

This repository contains two projects developed for the **Image and Vision Processing (PIV)** course at **ISEL**. Both projects are built with **Python** and **OpenCV**, and demonstrate practical applications of computer vision.

---
### 🧱 Lego-Classifier: Rectangular Lego Piece Counter

An algorithm that automatically identifies, counts, and classifies rectangular Lego bricks from an image.

* **Objective**: To gain experience with object classification using OpenCV.
* **How it Works**: The system processes an input image to isolate individual Lego pieces. It then analyzes properties like **area** and **dimensions** to classify each piece into categories like "2x2," "2x4," and so on, providing a final count.
* **Tech Stack**:
    * **Python**
    * **OpenCV** for image processing (binarization, contour extraction)
    * **NumPy** for numerical analysis

---
### 👋 Motion-Classifier: Real-time Hand Gesture Interface

A real-time system that estimates and classifies hand motions from a video feed to control a graphical application.

* **Objective**: To build a human-machine interface that translates hand gestures into interactive commands.
* **How it Works**: The system detects and tracks the hand, classifying movements into six types: **RIGHT**, **LEFT**, **UP**, **DOWN**, **ZOOM IN**, and **ZOOM OUT**. These classifications are used to animate a graphical object, creating a dynamic user experience.
* **Tech Stack**:
    * **Python**
    * **OpenCV** for real-time video processing
    * **Pygame/Blender/Unity** for graphical animation
