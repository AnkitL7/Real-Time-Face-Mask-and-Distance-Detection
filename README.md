# Face-Mask-and-Social-Distance-Detection
#### In this project, we bulid a Deep Learning Model based on MobileNetV2 and YOLOv3 to detect live Face Masks and Social Distancing respectively. MobileNetV2 and YOLO are used here in order to minimize the run time and maximize the Frames Per Second(FPS) when live inferencing, while not significantly sacrificing the accuracy. 

<br>

## Setting up the environment and installing the dependencies
* ***Open the Terminal**
* ***Change directory to where you want to downloaded this code***
* ***Run `git clone https://github.com/sagarmandiya/Face-Mask-and-Social-Distance-Detection.git`**
* **Creating a new conda environment after installing anaconda**  `  conda create -n ObjectDetection ` ***to create a virtual environment named ObjectDetection.***
* **Activate the ObjectDetection environment by**   `  conda activate ObjectDetection  python=>3.7` 
* **Run**   `  pip install -r requirements.txt  ` 
***to install the python dependencies related to this project like TensorFlow, opencv, numpy, scipy etc.***

## To run the inference on local machine:
* ***Open the terminal**
* **To Run the detection on a locally stored video named pedestrians.mp4 run** `python live_inference.py --input pedestrians.mp4 --output output.avi --display 1`
* **Whereas to run the detection live using the Webcam simply run** ` python live_inference.py `

#### **After you run the above line of command, a window will pop up depending upon your choice of live or locally stored video, and after execution of the file an `output.avi` file will be made in your directory if you chose the locally stored video option, otherwise webcam will open for live inference.**
<br>
