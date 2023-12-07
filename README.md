# Object Tracking using OpenCV

This Python script demonstrates object tracking in a video using OpenCV. It detects objects in each frame and tracks them over time based on their centroids. The tracking is performed by comparing the centroids of detected objects in consecutive frames.

## Prerequisites

- Python 3.x
- OpenCV (`pip install opencv-python`)
- NumPy (`pip install numpy`)

## Usage

1. Clone the repository:
   git clone https://github.com/AnshulPanchkaran/detection.git

2. navigate to the project directory 
   cd detection
3.run the script 
   python object_tracking.py

4.Press ESC key to exit the video window.


Certainly! Here's a simple README file for the provided Python script:

markdown
Copy code
# Object Tracking using OpenCV

This Python script demonstrates object tracking in a video using OpenCV. It detects objects in each frame and tracks them over time based on their centroids. The tracking is performed by comparing the centroids of detected objects in consecutive frames.

## Prerequisites

- Python 3.x
- OpenCV (`pip install opencv-python`)
- NumPy (`pip install numpy`)

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/your-repository.git
Navigate to the project directory:

bash
Copy code
cd your-repository
Run the script:

bash
Copy code
python object_tracking.py
Press ESC key to exit the video window.

Description
1.The script uses the ObjectDetection class for object detection. Ensure that this class is correctly implemented and imported from the object_detection module.
2.Detected objects are tracked across frames based on their centroids.
3.The distance threshold (60 in the provided script) determines when a detected object is considered the same as an object in the previous frame.
4.Each tracked object is assigned a unique ID, and the script displays the IDs next to the tracked objects.

Controls
Press ESC to exit the video window and terminate the script.


Note
Adjust the distance threshold and other parameters as needed for optimal object tracking performance.

Make sure to have the required video file (video.mp4) in the project directory or update the file path accordingly.

Feel free to modify the script and README according to your specific requirements and project structure.
