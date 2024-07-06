# automatic-license-plate-recognition-python-yolov8
## data
The video I used in this tutorial can be downloaded [here](https://www.pexels.com/video/traffic-flow-in-the-highway-2103099/).
## libraries:
Python libraries used include EasyOCR, YOLOv8, and OpenCV.
## models

A Yolov8 pretrained model was used to detect vehicles.

## License plate format:

The system is designed to work with a specific license plate format, which is the UK format with seven characters (two letters, two digits, and three letters).
The system can be adapted to work with other license plate formats.
Steps:

Load libraries and video:

The first step is to import the necessary libraries and load the video containing the cars.
Object detection:

YOLOv8 is used to detect cars in the video frames.
Object tracking:

Once cars are detected, a separate algorithm called SORT is used to track the motion of these cars across the video frames.
License plate recognition:

EasyOCR is then used to read the license plates from the detected cars.
Data storage (optional):

The results, including the license plate numbers and car IDs, can be saved to a CSV file for further analysis.

