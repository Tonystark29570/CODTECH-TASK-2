**NAME:** R.SIVAPRASATH                                                                                                                                                              .
**COMPANY:** CODTECH IT SOLUTIONS                                                                                                                                                    .
**ID:** CT08FAX                                                                                                                                                                      .
**DOMAIN:** ARTIFICIAL INTELLIGENCE                                                                                                                                                  .
**DURATION:** 20TH DECEMBER 2024 TO 20TH JANUARY 2025                                                                                                                                .

## OVERVIEW OF THE PROJECT

## PROJECT:COMPUTER VISION TASK

###Specific Problem

Task: Detect and classify objects in street scenes.
Objective: Build an object detection model to identify and locate common objects like cars, pedestrians, and traffic lights in urban environments.
Dataset: Use the COCO dataset (or download an open-source dataset of street scenes, such as the KITTI dataset).


1. Objective
The primary objective of this task is to design and implement an object detection model that can identify and locate objects such as cars, pedestrians, and traffic lights in urban street scenes. This capability is essential for applications like autonomous vehicles and traffic monitoring systems.


2. Features
Accurate Object Detection: Identifies and classifies objects.
Bounding Box Visualization: Displays detected objects with bounding boxes.
Real-Time Detection: Achieves detection at high speeds using YOLOv5.
Scalability: Handles various object types and urban environments.


3. Dataset
Dataset Name: COCO (Common Objects in Context)
Dataset Overview:
Train/Validation Split: 118,287 training images and 5,000 validation images.
Number of Classes: 80, including objects like person, bicycle, car, and traffic light.
Preprocessing:
Resized images to 640x640 pixels.
Normalized pixel values to [0, 1].


4. Methodology
Model: YOLOv5 (You Only Look Once), a single-stage object detector optimized for speed and accuracy.
Steps:
Prepared the COCO dataset in YOLO format.
Fine-tuned the YOLOv5s model using pre-trained weights.
Trained for 50 epochs with a batch size of 16 and an image size of 640x640.
Evaluated the model using validation data to compute mAP.



5. Technologies
Framework: PyTorch.
Tools: YOLOv5, OpenCV, and Python.
Hardware: NVIDIA GPU for accelerated training.



6. Results
Model Performance:
Achieved an mAP of 55.4% on the validation set.
Average inference speed: 25 FPS on a standard GPU.




7. Challenges and Improvements
Challenges:
Dataset preparation and annotation required significant effort.
Balancing speed and accuracy during training.
Improvements:
Experiment with larger models like YOLOv5x for higher accuracy.
Use real-time streaming data for deployment testing.



8. Conclusion
This project successfully implemented an object detection model using YOLOv5 to identify and locate objects in urban street scenes. The model achieved high accuracy and real-time performance, making it suitable for applications such as autonomous driving and traffic analysis.

![Screenshot 2024-12-29 140009](https://github.com/user-attachments/assets/62bec81c-83c2-42f3-b7a4-6f3f2335d4b2)
![Screenshot 2024-12-29 140030](https://github.com/user-attachments/assets/048eba04-b991-436c-b669-197610db23ed)
![Screenshot 2024-12-29 140647](https://github.com/user-attachments/assets/472e79b3-cef7-4c4c-871b-53ed821c5fa8)








