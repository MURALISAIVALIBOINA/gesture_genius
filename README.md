# Gesture Genius

Gesture Genius is a Python-based application that uses computer vision and hand tracking to recognize and respond to hand gestures. This project leverages OpenCV, MediaPipe, and autopy libraries to implement gesture-based controls for various functions.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Requirements](#requirements)
- [Technologies Used](#technologies-used)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Introduction
Gesture Genius allows users to interact with their computer using hand gestures. It utilizes a webcam to capture video, detect hands, and interpret gestures to perform actions such as moving the mouse, clicking, and pressing keys.

## Features
- **Gesture Recognition**: Recognizes various hand gestures using MediaPipe and performs corresponding actions.
- **Mouse Control**: Move the mouse cursor using hand movements.
- **Click and Key Press**: Use gestures to simulate mouse clicks and keyboard presses.
- **GUI**: A simple Tkinter-based GUI to start and stop the gesture recognition.

## Installation
To get started with Gesture Genius, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/MURALISAIVALIBOINA/gesture-genius.git
   cd gesture-genius
   ```

2. Install the required dependencies:
   ```bash
   pip install opencv-python mediapipe autopy pydirectinput
   ```

3. Download and save an image file named `img.png` in the project directory for the application icon.

## Usage
1. Run the application:
   ```bash
   python main.py
   ```

2. The Tkinter GUI will appear. Click the "START" button to begin gesture recognition.

3. The following gestures are supported:
   - **Single Finger Pointing**: Moves the mouse cursor.
   - **Thumb Up**: Left-click.
   - **All Fingers Up**: Scroll right.
   - **All Fingers Down**: Scroll left.
   - **Index, Middle, and Ring Fingers Up**: Press space.

4. Click the "EXIT" button to stop the recognition and close the application.

## Requirements
- **Python 3.8 or higher**
- **Hardware**:
  - **Webcam**: A good quality webcam for accurate hand tracking.
  - **CPU**: Intel i5 or equivalent for smooth processing.
  - **RAM**: At least 4GB for handling image processing.

## Technologies Used
- **OpenCV**: For video capture and image processing.
- **MediaPipe**: For hand tracking and gesture recognition.
- **autopy**: For controlling the mouse and keyboard.
- **pydirectinput**: For simulating key presses.
- **Tkinter**: For the graphical user interface.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Create a new Pull Request.

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/tweag/mediapipe-experiments/blob/master/LICENSE) file for details.

## Acknowledgements
- Inspired by various open-source projects and tutorials on gesture recognition.
- Thanks to the developers of OpenCV, MediaPipe, autopy, and other libraries used in this project.
