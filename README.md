# Custom_object_detection_YOLOv5
Here I use just one object [barcode] to detect in any form...
You can also use other classes of more than one.
YOLO is an abbreviation for the term 'You Only Look Once',which is an algorithm that detects and recognizes various objects in a picture/video/real-time. Object detection in YOLO is done as a regression problem by providing the class probabilities of the detected images and with that ratio it is then leads to our required result...


# How to run the program
1. First you have to create a dataset contains the pictures of different class name (person, book, cycle etc.).
2. Now clone this https://github.com/tzutalin/labelImg and follow exactly what it has mentioned from the **Installation part to the opening the file.**
3. Now you have to label them each and every picture in yolo format to get the positioning of each class. For that this tutorial https://www.youtube.com/watch?v=VAgEF6Dxsy4 will be really helpful for all versions of yolo.
4. You can follow this link too https://www.youtube.com/watch?v=zSda1AoUTkc as mentioned in the previous step.
5. After creating label for the respective class, split them into train and val for both images and for label...
6. After making them, now zip them, so it can be used in training for accuracy...


After this make a custom model:
1. If you have one class you can use my **custom_data** file.
2. If have more then increase the number of class count and label them in that list.
3. Finally run the yolov5_object detection
