Week 1 – Video Processing using FFmpeg

Task 1 – Extracting Images from Video

source video:https://youtu.be/NQ6_Sqt_w3Y?si=i0BON63Vr9wy8a6J

output:

<img width="640" height="360" alt="week1-1" src="https://github.com/user-attachments/assets/5f9341ac-9fc7-421e-a5b5-f4095243e096" />

<img width="640" height="360" alt="week1-1 2" src="https://github.com/user-attachments/assets/2d804423-9425-4f9e-9b9a-bc1da7dadc32" />

<img width="640" height="360" alt="week-1-1 3" src="https://github.com/user-attachments/assets/5111674e-3d2a-4e66-8e4d-68c96aa29142" />

Objective:

Learn how to extract multiple image frames from a video using FFmpeg.

Work Done:

Downloaded a short YouTube video using yt-dlp.

Extracted frames from the video using FFmpeg.

Verified extracted images.

Uploaded sample images and video links.

Commands Used:

yt-dlp <youtube_video_url>

ffmpeg -i input.mp4 frames/img_%04d.jpg



