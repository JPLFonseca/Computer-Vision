# Computer Vision Projects
This repository showcases two practical projects developed for the Image and Vision Processing (PIV) course at the Instituto Superior de Engenharia de Lisboa (ISEL). Both projects were developed using Python and the OpenCV library.

## Project 1: Rectangular Lego Piece Counting and Classification
This project, titled Lego-Classifier, is an algorithm designed to automatically identify, count, and classify rectangular Lego pieces from a given image.

### 📝 Overview
The main objective was to gain hands-on experience with object classification using the OpenCV library. The system takes an image of Lego pieces arranged on a surface and determines how many of each type ("2x2," "2x4," "2x6," and "2x8") are present.

### 🛠️ Technology
Python: The primary programming language.

OpenCV: Utilized for image processing tasks such as binarization, contour extraction, and property analysis.

NumPy: Used for numerical operations.

### 💡 Core Functionality
The algorithm works by processing an image to identify individual Lego pieces. It then calculates properties like area and dimensions to classify each piece and present a final count. The project also includes code to visualize color histograms to aid in image analysis.

## Project 2: Real-time Hand Motion Estimation and Classification
This project, named Motion-Classifier, focuses on creating an interactive graphical application that responds to hand movements captured from a video sequence.

### 📝 Overview
The goal was to develop a real-time system that estimates and classifies hand motions. This system acts as a human-machine interface, translating hand gestures into commands that control a simple graphical animation.

### 🛠️ Technology
Python: The main programming language.

OpenCV: Essential for processing video frames in real-time.

Pygame/Blender/Unity: The project description notes that one of these interfaces could be used for the graphical animation.

### 💡 Core Functionality
The system detects and tracks the hand in a video feed, using either image subtraction or skin tone detection in the RG-normalized color space. It then classifies movements into six types: RIGHT, LEFT, UP, DOWN, ZOOM IN, and ZOOM OUT. These classifications are used to animate a graphical object, providing an interactive experience.
