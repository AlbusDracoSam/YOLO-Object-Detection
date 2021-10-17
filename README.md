# YOLO

YOLO refers to “You Only Look Once” is one of the most versatile and famous object detection models. For every real-time object detection work,
YOLO is the first choice by Data Scientist and Machine learning engineers. 

YOLO algorithms divide all the given input images into the SxS grid system.
Each grid is responsible for object detection. Now those Grid cells predict the boundary boxes for the detected object.

For every box, we have five main attributes: x and y for coordinates, w and h for width and height of the object, and a confidence score for the probability
that the box containing the object.

1. 📁Folder structure :
	
  	-train_data
  
		-images
			-train
			-val
		-lables
			-train
			-val

	The folder must be in this format since coco yaml looks for annotated labels. 

2. Image annotation ✏️ is done using [Make Sense](https://www.makesense.ai/)

3. The export annotation should be in the form of a.zip file containing YOLO files.

4. Both the train and the val data should be annotated and saved in the labels folder.

5. Navigate 🚀 to [Ultralytics](https://github.com/ultralytics/yolov5) and open with colab.

6. Compress the images and labels in the train data folder into a compressed zip folder and upload it to colab.

7. Unzip the file in the colab.

8. Download ⬇️ the COCO128.yaml file from files -> yolov5 -> data.

9. Rename 📝 the file. Here we are only going with a single class called the 'chicken'. 

10. Edit the 'nc' i.e., number of classes. Here we give it as 1.

11. Change the train and val data path. 

12. Give the class name in names list.

13. Upload the edited yaml file again.

14. Train the dataset. 📚

Feel free to check the report here : [wandbi.ai](https://wandb.ai/ajithsam/YOLOv5/reports/Object-Detection-YOLOv5--VmlldzoxMTI3OTA3?accessToken=smkn0yk3s112y6ajt4rka6g4vca0wqjj7twfy8tb4qurvh7tvw47zyh6ikubf43i)
	





