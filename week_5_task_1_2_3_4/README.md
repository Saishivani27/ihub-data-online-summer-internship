Week 5 – Custom Model Training

output video : https://drive.google.com/file/d/1ZAFckIdrhU-MUsLywwClcx3hZ3fd2R6J/view?usp=sharing

dataset/
└── runs/
    └── detect/
        └── predict/
            ├── output.mp4
            ├── music.mp3
            ├── img_001.jpg
            ├── img_002.jpg
            └── ...

Task 1 – Annotation Completion

Objective:

Complete annotation process and organize dataset.

Work Done:

Verified all labels.

Created:

train.txt

val.txt

YAML file

Task 2 – Image Scaling using FFmpeg

Objective:

Resize images while maintaining aspect ratio.

Commands Used:

ffmpeg -i input.jpg -vf scale=384:-1 output.jpg

Task 3 – Training Custom YOLOv26 Model

Objective:

Train custom object detection model.

Commands Used:

yolo task=detect mode=train model=yolo11n.pt \

data=data.yaml epochs=100 imgsz=640

Work Done:

Trained model on custom dataset.

Observed training and validation losses.

Saved trained weights.

Task 4 – Testing Trained Weights

Objective:

Detect custom objects using trained weights.

Commands Used:

yolo task=detect mode=predict \

model=best.pt source=test_images/

