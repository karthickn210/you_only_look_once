# you_only_look_once

### Requirements
1. Tensorflow
2. OpenCV



### Installation

1. Clone yolov2_tensorflow repository
	```Shell
	$ git clone https://github.com/karthickn210/you_only_look_once.git
    $ cd yolov2_tensorflow
	```

2. Download [YOLO_v1](http://pan.baidu.com/s/1cGV694) [YOLO_v2_pb](http://pan.baidu.com/s/1hrRszrA) [YOLO_v2_meta](http://pan.baidu.com/s/1dEOaGPr) 
   put it in `models`

3. Modify configuration in `yolo/config.py` for yolov1

4. Run
	```Shell
	$ python demo_yolo_v1.py
	$ python demo_yolo_v2.py
	```
