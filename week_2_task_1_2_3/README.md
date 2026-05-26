Week 2 – Object Detection using YOLOv26

Task 1 – Creating Python Virtual Environment

Objective:

Set up an isolated Python environment for project development.

Work Done:

Created a virtual environment using venv.

Activated environment before installing dependencies.

Commands Used:

python -m venv yolo_env

source yolo_env/bin/activate

Task 2 – Installing Ultralytics

Objective:

Install Ultralytics package for YOLOv26.

Work Done:

Installed ultralytics package using pip.

Verified installation.

Commands Used:

pip install -U ultralytics

Task 3 – Running Object Detection

Objective:

Run pretrained YOLOv26 object detection on images/videos.

Work Done:

Loaded pretrained YOLOv26 model.

Performed object detection.

Generated annotated outputs.

Sample Code:

from ultralytics import YOLO

model = YOLO("yolo11n.pt")

results = model("image.jpg", save=True)
