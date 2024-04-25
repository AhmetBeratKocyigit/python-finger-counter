# Finger Counter

This Python script uses OpenCV and the cvzone library to count the number of fingers shown in a webcam feed.

## Requirements

- Python 3.x
- OpenCV (`pip install opencv-python`)
- cvzone (`pip install cvzone`)

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/AhmetBeratKocyigit/python-finger-counter
    ```

2. Navigate to the project directory:

    ```bash
    cd python-finger-counter
    ```

3. Run the script:

    ```bash
    python finger_counter.py
    ```

4. Enjoy counting your fingers!

## How it Works

1. The script captures frames from the webcam.
2. It detects hands using the HandTrackingModule from cvzone.
3. For each detected hand, it counts the number of fingers.
4. The finger count is displayed on the webcam feed in real-time.
