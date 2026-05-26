Week 1 – Video Processing using FFmpeg

Task 2 – Video Reconstruction from Frames

source video: https://youtu.be/oJDzh2mVBms?si=uRFvnEfBFRbWWaYH

output:https://drive.google.com/file/d/19sdCa5YUb3oUiPNYSe6hqEO92Rx8u4gG/view?usp=sharing

Objective:

Generate approximately 1800 frames from a 1-minute video and reconstruct the frames back into a video.

Work Done:

Extracted frames at 30 FPS.

Generated around 1800 images.

Reconstructed images back into a video using FFmpeg.

Commands Used:

ffmpeg -i input.mp4 -vf fps=30 frames/frame_%04d.jpg

ffmpeg -framerate 30 -i frames/frame_%04d.jpg output.mp4
