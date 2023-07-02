# Helmet_Detection-YOLOv8

#STEPS

1) Importing the necessary modules:
•import os
•from IPython import display
•import ultralytics
•from ultralytics import YOLO
•from IPython.display import display, Image.


2) Setting the current working directory:
•HOME = os.getcwd
•print(HOME)


3) Installing packages:
•!pip install ultralytics==8.0.20
•!pip install roboflow


4) Working with Roboflow: 
Creating a directory: !mkdir {HOME}/datasets
•Accessing and downloading a dataset from Roboflow
•from roboflow import Roboflow: Importing the Roboflow class from the roboflow module.
•Creating a Roboflow instance
•Accessing a specific project and downloading the dataset


  5) Running object detection training:
  •Setting the working directory back to HOME:       %cd {HOME}
  •Running the object detection training command:


  6)Listing files and directories:
  
  •!ls {HOME}/runs/detect/train/

  
  7)Displaying an image:
  
  •Setting the working directory back to HOME
  •Displaying an image using the Image class

