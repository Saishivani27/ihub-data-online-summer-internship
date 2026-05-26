Week 1 – Video Processing using FFmpeg

Task 3 – Adding Audio to Video

source video:https://youtu.be/oJDzh2mVBms?si=4mDyc_Gx2LjX6Cwn

audio:https://pixabay.com/music/ambient-michael-ihde-daydream-epic-dreamy-sci-fi-melody-meditation-score-109997/

output:https://drive.google.com/file/d/1EFS4KxctB3wdG6Iquf-MfIu05msmBVrd/view?usp=sharing

Objective:

Merge a 1-minute music clip with the reconstructed video.

Work Done:

Downloaded royalty-free music.

Trimmed audio using Audacity.

Added soundtrack to reconstructed video using FFmpeg.

Commands Used:

ffmpeg -i video.mp4 -i audio.mp3 -shortest final_output.mp4
