# YOLO

YOLO refers to “You Only Look Once” is one of the most versatile and famous object detection models. For every real-time object detection work,
YOLO is the first choice by Data Scientist and Machine learning engineers. 

YOLO algorithms divide all the given input images into the SxS grid system.
Each grid is responsible for object detection. Now those Grid cells predict the boundary boxes for the detected object.

For every box, we have five main attributes: x and y for coordinates, w and h for width and height of the object, and a confidence score for the probability
that the box containing the object.

1. Folder structure :
	
  -train_data
  
		-images
			-train
			-val
		-lables
			-train
			-val

	Since coco yaml looks for the annotated labels the folder must be in this format. 

2. Image annotation is done using https://www.makesense.ai/

3. The export annotation should be in A .zip package containing files in YOLO format.

4. Annotate both the train and val data and put it in the labels folder.

5. Navigate to https://github.com/ultralytics/yolov5 and open with colab.

6. Compress the train_data folder containing the images and label into a compressed zip folder and 	  upload the same to colab. 

7. Unzip the file in the colab.

8. Download the COCO128.yaml file from files -> yolov5 -> data.

9. Rename the file. Here we are only going with a single class called the 'chicken'. 

10. Edit the 'nc' i.e., number of classes. Here we give it as 1.

11. Change the train and val data path. 

12. Give the class name in names list.

13. Upload the edited yaml file again.

14. Train the dataset. 





