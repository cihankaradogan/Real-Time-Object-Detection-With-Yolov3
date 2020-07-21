# Real-Time-Object-Detection-With-Yolov3
**Usage**

python yolo.py -w="The path of the weight file" -cfg="The path of the cfg file" -v="The path to the video file" -vo="The path of the output video file(deafult=./output.mp4)" -l="The path of the label file"

**Example**

python yolo.py -w=yolov3-tiny.weights -cfg=yolov3-tiny.cfg -v=videoplayback.mp4 -l=coco.names
