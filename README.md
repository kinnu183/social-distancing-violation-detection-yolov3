# social-distancing-violation-detection-yolov3

Yolov3 was used to detect people in the video sequences.

We used three yolo weights (Pre-trained speed optimised weight file) to train the model-
320, 416 and 608 COCO datasets

When model is trained with different weights, there will be a tradeoff between speed and accuracy.

Apply non-max suppression (a technique used in numerous computer vision tasks. It is a class of algorithms to select one bounding box out of many overlapping bounding boxes).

Libraries used -
cv2
numpy
time
