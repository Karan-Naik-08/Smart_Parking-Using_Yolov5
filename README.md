# Smart_Parking-Using_Yolov5
Trained a model using yolov5 that detect available space in parking lot

Recommended to run this on Google Colab as it works smoothely (Coz My laptop was not able to handle it training process).
Google Colab works best in my case.

First to Run this code first create a folder SmartParking in your drive and upload yolov5,CarP and train_data in this folder.
If there is update in yolov5 version download it from official github of yolov5(https://github.com/ultralytics/yolov5.git) and pastethe file custom1.yaml(which is located in Changed File Folder) to yolov5>data folder 

Now open Copy_of_YOLOv5_Tutorial.ipynb in google colab and run the first step , This will mount your drive to the colab file and now we can acces files from drive to colab.

If you have created the Folder as mentioned you don't need to change anything (but if name of folder is different then change the directory accordingly "it should direct towards yolov5 folder")

Then follow the steps mentioned In Copy_of_YOLOv5_Tutorial.ipynb this shall work fine .
