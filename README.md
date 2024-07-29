# object_tracking_using_openCV-python

This project demonstrates object tracking using OpenCV and Python. The main goal is to detect and track objects in video streams or real-time video from a camera.

Features
Object detection using various methods
Real-time object tracking
Support for multiple tracking algorithms
Easy-to-use interface
Requirements
Python 3.x
OpenCV 4.x
Numpy
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/object-tracking-opencv.git
cd object-tracking-opencv
Install the required packages:

bash
Copy code
pip install -r requirements.txt
Usage
To run the object tracker on a video file:

bash
Copy code
python object_tracker.py --video path/to/video.mp4
To run the object tracker using the webcam:

bash
Copy code
python object_tracker.py
Available tracking algorithms:

BOOSTING
MIL
KCF
TLD
MEDIANFLOW
GOTURN
MOSSE
CSRT
Example:

bash
Copy code
python object_tracker.py --tracker KCF
Example

Files
object_tracker.py: Main script for object tracking
requirements.txt: List of required packages
example.gif: Example of object tracking
Contributing
Contributions are welcome! Please fork the repository and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgments
OpenCV library for providing robust computer vision functionalities
Python community for various resources and tutorials
