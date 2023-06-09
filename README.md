# Hand-Distance
## Hand-to-Webcam Distance Measurement

This project uses Python and OpenCV to measure the distance between a user's hand and the webcam. By leveraging computer vision techniques, it provides a simple way to estimate the distance in real-time.

## Requirements

Libraries required for this project are given the in the `requirement.txt` file


## Usage

1. Clone or download the project repository to your local machine.
2. Ensure that Python3 is installed on your system.
3. Connect a webcam to your computer and ensure it is functioning properly.
4. Open the terminal and navigate to the project directory.
5. Install the necessary dependencies by running the following command in your terminal:
```python
pip install -r requirement.txt
```
6. Run the following command to start the distance measurement:
```python
python3 main.py
```
This will activate the webcam and open a new window showing the live video feed.
7. Place your hand in the frame, making sure it is clearly visible to the webcam.
8. Observe the distance value displayed on the screen. This value represents the estimated distance between your hand and the webcam.

**Note**
Please note that the distance estimation provided by this project is approximate and depends on various factors such as camera resolution, lighting conditions, and the size of the user's hand.
