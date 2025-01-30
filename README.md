# Optiprints
Optiprints

QR Code-Based Material Detection and Positioning App

Founder: Daulet Kaparov | September 2024 – Present

Overview

Optiprints is a cross-platform desktop application designed for real-time material detection and QR code scanning. By leveraging advanced computer vision algorithms and AI-driven object detection, the application enhances material utilization and positioning accuracy, making it a valuable tool for precision manufacturing, material cutting, and automation processes.

Features

Real-Time Material Detection: Utilizes computer vision algorithms to identify and analyze materials.

AI-Powered Object Recognition: Trained an AI model for object detection, image classification, and segmentation to enhance accuracy.

Optimized Cutting Positioning: Implements mathematical models to determine optimal cutting positions based on SVG input and scanned material.

High-Speed QR Code Scanning: Achieved a 4× faster scanning rate, improving workflow efficiency.

Binary Mapping System: Designed for precise paper placement, with structured data storage via SQLite.

IoT Integration: Real-time USB camera control via Blynk IoT for seamless operation and file conversion (DWG/SVG).

Technologies Used

Programming Languages: Python, JavaScript (Electron.js)

Computer Vision: OpenCV, TensorFlow

Database Management: SQLite

IoT Integration: Blynk IoT

File Formats: DWG, SVG

Installation

Clone the repository:

git clone https://github.com/DauletKaparov/optiprints.git

Install dependencies:

npm install  # For Electron dependencies

Run the application:

npm start  # Start the Electron.js application

Usage

Connect a USB camera.

Load the SVG/DWG file for material cutting.

The app will scan the QR code and detect the material.

The optimized cutting position will be displayed and executed.

Contribution

Contributions are welcome! Feel free to fork the repository, submit issues, or create pull requests.

License

This project is licensed under the MIT License - see the LICENSE file for details.

For more details, contact kaparovdaulet0805@gmail.com
