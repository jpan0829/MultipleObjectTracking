Understand the problem and setup environment

Detecting moving objects in each frame. Using YOLOv3 for object detection.load the pre-trained configuration and weights, as well as the class names of the COCO dataset on which the Darknet model was trained.Last, displaying it with the bounding boxes around detected objects

Tracking the moving objects from frame to frame. In addtion to YOLOv3 detector, applying a Kalman filter to predict the track of previously identified objects, and match them with new detections. Kalman filter works by a two-phase process. For the prediction phase, the Kalman filter produces estimates of the current state variables, along with their uncertainties. During update, these estimates are updated using a weighted average, with more weight being given to estimates with greater certainty.

