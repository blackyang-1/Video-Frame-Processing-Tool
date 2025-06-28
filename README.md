# Video-Frame-Processing-Tool
A simple Python project based on the OpenCV library for converting between videos and frames. 
If your FFmpeg installation is not working properly, this project offers an alternative solution.
Two main feature:
1. Extract frames from video (e.g., mp4 to jpg).
2. Rebuild video from frames (e.g., jpg to mp4).

Install Opencv library:
```bash
 pip install opencv-python
```

Usage for py file:

1.video to frames
```bash
python video_frame_process.py --mode vtf --video_path Example_video.mp4 --output_path Example_frames
```

2.frames to video
```bash
python video_frame_process.py --mode ftv --frames_folder Example_frames --output_path Example_synthesize_video.mp4 --fps 30
```
