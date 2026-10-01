#AI Virtual Mouse Controller

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Latest-orange)

A real-time, touchless mouse controller built with Computer Vision. This project translates hand gestures into PC commands using a webcam, allowing you to control your cursor, click, and scroll without touching any physical device.

## Features

- **Cursor Tracking:** Move your mouse smoothly by pointing your index finger.
- **Dynamic Mapping:** Uses mathematical interpolation to map a small "active box" from the camera frame to your full screen resolution.
- **Gesture Clicks:** 
  - *Left Click:* Touch your thumb and index finger.
  - *Double Click:* Touch your thumb and middle finger.
- **Scroll Mode:** Raise both index and middle fingers (peace sign) to activate vertical scrolling.
- **Motion Smoothing:** Built-in dampening algorithm to reduce jitter and ensure a stable cursor.

## Tech Stack

- **Python** 
- **OpenCV** (Image processing & webcam capture)
- **MediaPipe** (Hand landmark detection)
- **PyAutoGUI** (OS mouse control)
- **NumPy** (Mathematical operations and interpolation)

## Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Reda-Mota/Click_Scrolling_by_Hand.git](https://github.com/Reda-Mota/Click_Scrolling_by_Hand.git)
   cd Click_Scrolling_by_Hand
