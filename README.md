# Virtual Paint

## Overview

Virtual Paint is a simple computer vision project using OpenCV in Python to create a virtual painting experience. The program allows users to draw on a canvas using different colors by waving specific objects in front of a camera.

## Features

- Detects and tracks predefined colors in real-time.
- Draws on the canvas based on the detected colors.
- Adjustable camera settings for better color detection.
- Simple and intuitive user interface.

## Requirements

- Python 3.x
- OpenCV
- NumPy

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/virtual-paint.git
   cd virtual-paint

## Install the required dependencies

  ```bash
pip install opencv-python numpy

## Run the Virtual Paint program:
  ```bash
python virtual_paint.py

## Adjust camera settings if needed.

Wave objects with predefined colors in front of the camera to draw on the canvas.

## Configuration
myColors: A list of color ranges in HSV format for detection.
myColorsValues: Corresponding BGR color values for drawing.
Camera settings (cap.set) can be adjusted for width, height, and brightness.
Usage
Press 'q' to exit the program.
Contributing
Contributions are welcome! Feel free to open issues or pull requests.

## License
This project is licensed under the ### DA.

