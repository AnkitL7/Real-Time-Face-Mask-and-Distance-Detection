# Face-Mask-and-Social-Distance-Detection
#### In this project, we bulid a Deep Learning Model based on MobileNetV2 and YOLOv3 to detect live Face Masks and Social Distancing respectively. MobileNetV2 and YOLO are used here in order to minimize the run time and maximize the Frames Per Second(FPS) when live inferencing, while not significantly sacrificing the accuracy. Working of the model [Video](https://drive.google.com/file/d/1ki2M_mHLPwd6p-xwYO-mo5DGLiAqoTbF/view?usp=share_link)
<br>

## To run the inference on local machine:
* ***Download yolov3 weights from [Here](https://drive.google.com/drive/folders/1jLBZ1CM5dCwT6qMZDcElyJoZY-8NNTXH?usp=share_link) and put it inside yolo-coco folder.
* ***Open the terminal**
* **To Run the detection on a locally stored video named pedestrians.mp4 run** `python live_inference.py --input pedestrians.mp4 --output output.avi --display 1`
* **Whereas to run the detection live using the Webcam simply run** ` python live_inference.py `

#### **After you run the above line of command, a window will pop up depending upon your choice of live or locally stored video, and after execution of the file an `output.avi` file will be made in your directory if you chose the locally stored video option, otherwise webcam will open for live inference.**
<br>
