Week 1 – Video Processing using FFmpeg
Task 1 – Extracting Images from Video
source video:https://youtu.be/NQ6_Sqt_w3Y?si=i0BON63Vr9wy8a6J
Objective

Learn how to extract multiple image frames from a video using FFmpeg.

Work Done:

Downloaded a short YouTube video using yt-dlp.

Extracted frames from the video using FFmpeg.

Verified extracted images.

Uploaded sample images and video links.

Commands Used:

yt-dlp <youtube_video_url>

ffmpeg -i input.mp4 frames/img_%04d.jpg

Output:

Multiple image frames extracted from the video stream.

Learning Outcomes
Understanding video decomposition
Frame extraction techniques
Basic FFmpeg usage
References
FFmpeg Documentation:
https://ffmpeg.org/documentation.html
yt-dlp GitHub:
https://github.com/yt-dlp/yt-dlp
FFmpeg Image Extraction Tutorial:
https://shotstack.io/learn/use-ffmpeg-to-convert-images-to-video/
