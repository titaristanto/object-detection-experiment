# Object detection
This is an object detection experiment using YOLO3

# How to run the image detection
First, download weight file by running `wget https://pjreddie.com/media/files/yolov3.weights
` on the main directory
To apply the detection algorithm on an image, simply run `python detector.py --images <image-file-name.png> --det det`.
The resulting detections will be printed on the image. Check the result in `det` folder