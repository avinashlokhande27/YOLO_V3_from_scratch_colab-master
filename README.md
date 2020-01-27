# YOLO_V3

| Plugin | README |
| ------ | ------ |
| YOLO: Real-Time Object Detection | [https://pjreddie.com/darknet/yolo/][PlDb] |
| GitHub implementation | [https://github.com/AvivSham/YOLO_V3_from_scratch_colab][PlGh] |

 
### Set up and running 

Main file is Detection.ipynb(juypter notebook hosted on google colab)

It requires you to mount the google drive to run.

Install the dependencies and devDependencies and start the server.

```sh
$ from google.colab import drive
$ drive.mount('/content/drive')
```
Here you need to load darknet & util modules in addition to the pallete file
```sh
$ !pip install torch==1.3.1
$ !wget https://raw.githubusercontent.com/AvivSham/YOLO_V3_from_scratch_colab/master/util.py
$ !wget https://raw.githubusercontent.com/AvivSham/YOLO_V3_from_scratch_colab/master/darknet.py
$ !wget https://raw.githubusercontent.com/AvivSham/YOLO_V3_from_scratch_colab/master/pallete
```

# Load 
```sh
$ yolo weight 
$ yolo cfg
$ the weight are from pretained model
$ net = cv2.dnn.readNet("/content/yolov3.weights", "/content/yolov3.cfg")
$ setting up the path to video file 
$ videoPath = '/content/drive/My Drive/colab-yolo/walking.mp4'
$ cap = ### Set up and running 

Main file is Detection.ipynb(juypter notebook hosted on google colab)

It requires you to mount the google drive to run.

Install the dependencies and devDependencies and start the server.

```sh
$ from google.colab import drive
$ drive.mount('/content/drive')
```
Here you need to load darknet & util modules in addition to the pallete file
```sh
$ !pip install torch==1.3.1
$ !wget https://raw.githubusercontent.com/AvivSham/YOLO_V3_from_scratch_colab/master/util.py
$ !wget https://raw.githubusercontent.com/AvivSham/YOLO_V3_from_scratch_colab/master/darknet.py
$ !wget https://raw.githubusercontent.com/AvivSham/YOLO_V3_from_scratch_colab/master/pallete
```

# Load 
```sh
$ yolo weight 
$ yolo cfg
$ the weight are from pretained model
$ net = cv2.dnn.readNet("/content/yolov3.weights", "/content/yolov3.cfg")
$ setting up the path to video file 
$ videoPath = '/content/drive/My Drive/colab-yolo/walking.mp4'
$ cap = cv2.VideoCapture(videoPath)
```

# take away!
  - per each frame you can detect the object and  accuracy
  - anchor box around each object


You can also:
  - Save files to GitHub,Google Drive, or on local
  - using torch version 1.31

# Notebook!
  - Juyptercv2.VideoCapture(videoPath)
```

# take away!
  - On each frame you can detect the object and accuracy
  - anchor box around each object

You can also:
  - Save files to GitHub,Google Drive, or on local
  - using torch version 1.31
  - enable the VideoCapture and genrate result on real time
  - Here ofline video is used which is mounted from google drive
  - due to space contrain i have saved only two frame and extend to required time


# Notebook!
  - Juypter
