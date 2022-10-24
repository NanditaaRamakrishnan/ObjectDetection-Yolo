# ObjectDetection-Yolo
Object detection is a phenomenon in computer vision that involves the detection of various objects in digital images or videos. Some of the objects detected include people, cars, chairs, stones, buildings, and animals.

This phenomenon seeks to answer two basic questions:

What is the object? This question seeks to identify the object in a specific image.
Where is it? This question seeks to establish the exact location of the object within the image.
Object detection consists of various approaches such as fast R-CNN, Retina-Net, and Single-Shot MultiBox Detector (SSD). Although these approaches have solved the challenges of data limitation and modeling in object detection, they are not able to detect objects in a single algorithm run. YOLO algorithm has gained popularity because of its superior performance over the aforementioned object detection techniques.

## What is YOLO?

YOLO is an abbreviation for the term ‘You Only Look Once’. This is an algorithm that detects and recognizes various objects in a picture (in real-time). Object detection in YOLO is done as a regression problem and provides the class probabilities of the detected images.

YOLO algorithm employs convolutional neural networks (CNN) to detect objects in real-time. As the name suggests, the algorithm requires only a single forward propagation through a neural network to detect objects.

This means that prediction in the entire image is done in a single algorithm run. The CNN is used to predict various class probabilities and bounding boxes simultaneously.

## Impotance of YOLO

YOLO algorithm is important because of the following reasons:

Speed: This algorithm improves the speed of detection because it can predict objects in real-time.
High accuracy: YOLO is a predictive technique that provides accurate results with minimal background errors.
Learning capabilities: The algorithm has excellent learning capabilities that enable it to learn the representations of objects and apply them in object detection.

## Working of YOLO alogrithm

YOLO algorithm works using the following three techniques:

Residual blocks
Bounding box regression
Intersection Over Union (IOU)


### Residual blocks
First, the image is divided into various grids. Each grid has a dimension of S x S. The following image shows how an input image is divided into grids.

### Bounding box regression
A bounding box is an outline that highlights an object in an image.

Every bounding box in the image consists of the following attributes:

Width (bw)
Height (bh)
Class (for example, person, car, traffic light, etc.)- This is represented by the letter c.
Bounding box center (bx,by)

### Intersection over union (IOU)
Intersection over union (IOU) is a phenomenon in object detection that describes how boxes overlap. YOLO uses IOU to provide an output box that surrounds the objects perfectly.

Each grid cell is responsible for predicting the bounding boxes and their confidence scores. The IOU is equal to 1 if the predicted bounding box is the same as the real box. This mechanism eliminates bounding boxes that are not equal to the real box.


https://www.section.io/engineering-education/introduction-to-yolo-algorithm-for-object-detection/
