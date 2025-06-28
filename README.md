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

Usage:
```bash
video_to_frames('eg.mp4','out_frames')
frames_to_video('frames', 'output_video.mp4', fps=30)
```
