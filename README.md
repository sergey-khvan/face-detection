# face-detection

## Model created on a custom dataset, using pretrained YOLO v8.

1. Captured 90 images from the webcam
2. Labeled the data in labelme
3. Splitted to Train/Val/Test 0.8/0.1/0.1
4. Augmented data using albumentations
5. Trained the model on train dataset
6. Validated and Tested using map50 metrics

The same logic may be used for any other object detection.

Locally tested on the webcam.

Inspired by github.com/nicknochnack 's video on facedetection
