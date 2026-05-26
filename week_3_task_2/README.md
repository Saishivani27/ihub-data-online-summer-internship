Week 3 – Semantic Segmentation

Task 2 – Video Stacking using FFmpeg

source video:https://youtu.be/ChxDEAN8EtY?si=_VyQHRhqi6HTz55q

output video:https://drive.google.com/file/d/1HCPreI9ZXT_4LQ7iyhnQhz1Kjygcl1d9/view?usp=sharing

Objective:

Combine raw, detected, and segmented videos vertically.

Commands Used:

ffmpeg -i raw.mp4 -i detect.mp4 -i segment.mp4 \

-filter_complex vstack=3 stacked.mp4
