# Test1-floss-Creatives
Create a system that detects and masks street signs and ad boards from the given video.
Here used a yolov5 model to solve this problem.
First we need to annotate the given image data of street and sign boards
1. use this link to create the annoted data in yolo format https://www.youtube.com/watch?v=DxyzUNhJTe0
2. use this https://github.com/ultralytics/yolov5 then select open in colab
3. create a folder on colab named 'train_data'
4. train data has 2 sub folders named as 'images' & 'labels'
5. 'images' and 'labels' each has 2 more sub folders named as 'train' & 'val' 
6. image folder has jpg files while label folder contains yolo format label files
