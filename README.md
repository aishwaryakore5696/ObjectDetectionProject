# ObjectDetectionProject
Output the coordinates for the bounding boxes containing the twitter “following button”.
Name-Aishwarya Kore Email-adk497@nyu.edu

This project aims at finding the location of the following button on given images.

Input images-https://www.dropbox.com/sh/qvf4ndku92ap725/AAAK53j-IxCawrtBPETCkT1-a?dl=0

My approch-
1)Train the YOLO for object detection with CV2 using the images given above- 
	Train_YoloV3_generate_weights.ipynb 
2)Download the weights-
	yolov3_training_last .weights
3)Used the above weights to detect follow object in the image- 
	yolo_object_detection_testing.py & 
	yolov3_testing.cfg
4)The result images with bounding boxes around the following button are stored in results folder
5)The video is also attached showing the working of the results.- videoresult

Thank you.
