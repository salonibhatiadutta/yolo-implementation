# yolo-implementation
To describe the yolo implementation and algorithm
Steps for Yolo implementation:
a) Reading of the required yolo version weights and configuration file(cfg)[downloaded from yolo algorithm official website)
b) coco.names file consists of the classes name which can be detected through yolo (80 classes)
c) reading the images and saving the weight and height in a variables
d)converting the BGR image to RGB for yolo algorithm and resizing the image using cv2.dnn.blobfromImage
e) setting the input image for yolo algorithm
f) setting the connection for image in the output layer
g) creating the bounding boxes and deciding the confidence level which needs to be shown
h) using the Non Max suppression algorithm for avoiding multiple detections
i) detecting the required object
