Week 3 – Semantic Segmentation

Task 1 – Semantic Segmentation

Performance Metrics:

Precision: ~0.64

Recall: ~0.52

mAP50: ~0.59

mAP50-95: ~0.39

source video: https://youtu.be/ChxDEAN8EtY?si=_VyQHRhqi6HTz55q

output video: https://drive.google.com/file/d/1H152uQHrkh77MAuehGX5tNtdLGk1jizV/view?usp=sharing

Objective:

Perform semantic segmentation on images using Ultralytics.

Work Done:

Applied semantic segmentation on training images.

Generated segmented outputs.

Reconstructed segmented video.

Sample Code:

from ultralytics import YOLO

model = YOLO("yolo11n-seg.pt")

results = model("image.jpg", save=True)
