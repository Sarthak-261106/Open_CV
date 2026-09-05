Assignment 11: Computer Vision with OpenCV
OpenCV - Image and Video Processing
A comprehensive collection of computer vision applications built using OpenCV (cv2) demonstrating various image processing techniques, transformations, filters, and video recording capabilities.

📌 Project Overview
Description
A fully functional computer vision project that demonstrates multiple image processing operations including resizing, morphological transformations, flipping, shifting, rotation, thresholding, edge detection, blurring filters, and video recording/playback from webcam.

Features
📐 Image resizing with aspect ratio maintenance
🔄 Morphological operations (Erosion, Dilation, Opening, Closing, Gradient, Top Hat, Black Hat)
🔃 Image flipping (Vertical, Horizontal, Both)
📍 Image shifting and rotation
🎯 Binary thresholding and edge detection
🌫️ Blurs (Gaussian, Median) & Filter (Bilateral)
📹 Video recording from webcam
💾 Video saving with custom overlays
▶️ Video playback
📂 Project Structure
assignment-OpenCV/
├── image.py                      # Image reading, resizing, and writing
├── morph.py                      # Morphological operations
├── flip.py                       # Image flipping with text labels
├── shift_rotate.py               # Image shifting and rotation
├── thres_edge.py                 # Thresholding and edge detection
├── blur_filter.py                # Blur and filter operations
├── video.py                      # Webcam recording and playback
├── dragon.jpg                    # Sample input image
├── Output.mp4                    # Recorded video output (generated)
├── screenshots/
│   ├── blur_filter_output.png
│   ├── flip_output.png
│   ├── image_output.png
│   ├── morph_output1.png
│   ├── morph_output2.png
│   ├── morph_output3.png
│   ├── morph_output4.png
│   ├── shift_rotate_output.png
│   ├── thres_edge_output.png
│   ├── video_output1.png
│   └── video_output2.png
└── README.md                     # This documentation file
🚀 How to Run
Prerequisites
Python 3.x installed
OpenCV library
NumPy library
Webcam (for video recording)
Installation Steps
Install required packages:
pip install opencv-python
pip install numpy
Prepare input image:
Place an image named dragon.jpg in the project folder
Or update the file path in the code
Run individual scripts:
# Image resizing
python image.py

# Morphological operations
python morph.py

# Image flipping
python flip.py

# Shifting and rotation
python shift_rotate.py

# Thresholding and edge detection
python thres_edge.py

# Blur filters
python blur_filter.py

# Video recording (requires webcam)
python video.py
