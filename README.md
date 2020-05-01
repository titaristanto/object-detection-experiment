# Object detection
This is an object detection experiment using YOLO3

# How to run the image detection
First, download weight file by running `wget https://pjreddie.com/media/files/yolov3.weights
` on the main directory
To apply the detection algorithm on an image, simply run `python detector.py --images <image-file-name.png> --det det`.
The resulting detections will be printed on the image. Check the result in `det` folder

# How to run the video detection
First, download weight file by running `wget https://pjreddie.com/media/files/yolov3.weights
` on the main directory
Put sample video in the main directory. You can use any video you want. A sample video can be downloaded from here `https://media.istockphoto.com/videos/friends-driving-4x4-cars-down-the-road-video-id507644002`
Run the detection algorithm by executing `python video_detector.py --video <video-file-name.mp4>`