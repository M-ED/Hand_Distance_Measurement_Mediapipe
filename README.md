
# Hand Distance Measurement and Interactive Game

This project demonstrates a hand distance measurement system using a webcam, along with a simple interactive game that detects hand movements and tracks the distance between specific landmarks on the hand. The project leverages Python libraries such as OpenCV, cvzone, and Mediapipe's HandTrackingModule.





## Features

- **Real-time Hand Detection:** Detects the hand and its landmarks in real-time using the webcam.
- **Distance Measurement:** Measures the distance between the base of the palm and the tip of the little finger using Euclidean distance.
- **Interactive Game:** A simple game that tracks hand movements and requires the player to "touch" a randomly appearing circle to score points.
### How it works

1.  **Hand Detection:** When the webcam is activated, it detects your hand and calculates the distance between two specific landmarks.
2.  **Interactive Game:** The game begins as soon as the script runs. Your goal is to touch the circle with your hand, which will move to a new random position after being "touched". The score is displayed on the screen, and the game ends after a set time.
## Prerequisites
- Python 3.9.0 or higher 
- OpenCV
- Mediapipe

## Installation

1. Clone the repository:

```bash
  git clone https://github.com/M-ED/Hand_Distance_Measurement_Mediapipe.git
```
2. Create virtual environment using following commands:
```bash
  conda create -n projects_CV python==3.9.0
  conda activate projects_CV
```

3. Install the necessary libraries in requirements file
```bash
   pip install -r requirements.txt
```

4. Run the file using command
```bash
   python main.py
```
## Acknowledgements

- OpenCV: [https://opencv.org/](https://opencv.org/)
- MediaPipe: [https://ai.google.dev/edge/mediapipe/solutions/guide](https://ai.google.dev/edge/mediapipe/solutions/guide)




## License

[MIT](https://choosealicense.com/licenses/mit/)


## Badges

Add badges from somewhere like: [shields.io](https://shields.io/)

[![MIT License](https://img.shields.io/badge/License-MIT-green.svg)](https://choosealicense.com/licenses/mit/)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)


## Author

- [@mohtadia_naqvi](https://github.com/M-ED)

