Face Recognition Attendance System
Project Description:
This project implements a real-time face recognition attendance system using Python and OpenCV. The system captures live video from a webcam, detects faces, and compares them with known faces stored in the ImagesAttendance folder. If a match is found, the system marks the attendance and logs the timestamp in a CSV file (Attendance.csv). If a face doesn't match any known faces above a certain confidence level, it saves the face image in the UnknownFaces folder for further review.

Getting Started:
Setup:

Clone the repository to your local machine.
Ensure you have Python and the necessary libraries installed (opencv-python, numpy, face_recognition).
Add Images:

Place images of individuals whose attendance you want to track in the ImagesAttendance folder. Ensure each image is named with the person's name or identifier.
Run the Program:

Execute the main.py script.
The webcam will start capturing video. Faces detected will be matched against the images in ImagesAttendance.
Attendance Records:

Attendance is recorded in real-time in the Attendance.csv file, including timestamps of when individuals are detected.
Notes:
Adjust the confidence threshold (confidence > 50) in main.py to control the sensitivity of face recognition.
Review faces saved in the UnknownFaces folder periodically to identify unrecognized individuals.
