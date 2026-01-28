# Human-pose-detection-using-mediapipe

Pose estimation refers to computer vision techniques that detect human figures in images and video, so that one could determine, for example, where someone’s elbow shows up in an image.
This project implements a real-time human pose detection system using MediaPipe and OpenCV. It detects and tracks human body landmarks from images, videos and also in real time by the help of webcam , enabling accurate posture and movement analysis. The system processes frames efficiently to achieve smooth, real-time performance.


# 🎯 Objectives

* Detect full-body human poses in real time </br>
* Track and visualize key body landmarks </br>
* Analyze posture and movement patterns </br>
* Build a foundation for applications like fitness tracking, gesture recognition, and activity monitoring </br>

# Technologies Used

* Programming Language: Python</br>
* Libraries & Frameworks: </br>
MediaPipe (Pose Estimation) </br>
OpenCV (Computer Vision)</br>
NumPy (Numerical Processing) </br>
Matplotlib (Plot creation) </br>



 # How It Works

MediaPipe pose estimation is a single 3D pose estimator. It detects x, y, and z coordinates for each landmark. Z-axis is basically information about the depth of a landmark. That means how far or close the landmarks are from the camera relative to the other landmarks.

* Capture video frames using OpenCV
* Convert frames to RGB format
* Apply MediaPipe Pose model for landmark detection
* Extract and process body keypoints
* Visualize landmarks and pose connections on frames
 <img width="910" height="418" alt="image" src="https://github.com/user-attachments/assets/7a405eff-170f-40d8-8b9f-2aa9688dc5ac" />

# System Features

* Real-time pose detection at 30+ FPS
* Detection of 33 body landmarks per person
* Works with webcam and video files
* Lightweight and efficient pipeline
* Visual landmark overlay with skeletal connections

<img width="1295" height="403" alt="image" src="https://github.com/user-attachments/assets/7af6f292-08ba-4c98-83e2-67bc55b4f531" />
<img width="880" height="695" alt="image" src="https://github.com/user-attachments/assets/b7e89583-f655-476e-9bd4-714e083de674" />

# Project Highlights

* Processed real-time video streams with minimal latency
* Achieved accurate landmark detection across multiple poses
* Optimized frame processing to reduce lag by ~35%
* Captures real time video by webcam


![20260128-0909-27 0418515](https://github.com/user-attachments/assets/9927182b-5694-4520-a3bd-2aa8d1e72f76)


# Applications

* Fitness and workout tracking
* Posture correction systems
* Sports performance analysis
* Gesture and activity recognition



# 🤝 Contributing

Contributions are welcome! Feel free to fork the repository and submit a pull request.

# Contact

For questions or suggestions, feel free to connect:

Name: Adarsh </br>
Linkedin: https://www.linkedin.com/in/adarsh-dwivedi-4a1241334?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BnXBVVtntT5Km%2BYSNLlJBCQ%3D%3D


# ⭐ If you like this project, don’t forget to star the repository!
