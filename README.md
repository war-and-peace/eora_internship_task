# eora_internship_task

## Instructions

### How to run the code on video file.
In order to run the code using recorded video file, the path to the file should be specified in command line argument video as follows:

     python detect_blink.py --shape-predictor shape_predictor_68_face_landmarks.dat --video video.mkv
  Here, video.mkv is the name of the video file. 

In order to run the code using on video camera in real time, just do not specify the video file path. It looks as follows:

    python detect_blink.py --shape-predictor shape_predictor_68_face_landmarks.dat

## Notes
The code is optimized for the video file that is uploaded to the GitHub - video.mkv. For other video files the result may be not satisfying, although simple parameter tuning solves the problem.
