# Face-Detection
FACE DETECTION
Face detection is a computer technology being used in a variety of applications that identifies human faces in digital images. Face detection can be regarded as a specific case of object-class detection, which focuses on the detection of frontal human faces. Because faces are so complicated, there isn’t a straightforward test that will tell if we found a face or not. Instead, thousands of small patterns and features must be matched for accurate facial detection.

Question:
Implement a face tracking algorithm using haar cascade algorithm and opencv. Using haar cascade, first implement a face detection algorithm that counts the total number of faces present in any given frame. Write the total number of faces detected on the top left of the image. Further modify the code to track the face if only one face is detected. Make sure that you draw the bounding box corresponding to all video frames. Note: you may need to fine tune the parameters for Haar Cascade Classifier to get optimal results and remove false positives

Procedure:
- import libraries
- Load the pre-trained Haar Cascade classifier for face detection
- Initialize the video capture
- Convert the frame to grayscale for face detection
- Perform face detection
- Draw bounding boxes around the detected faces and count them
- Display the number of faces detected in the top left corner of the frame
- Display the frame
- Exit loop if 'q' key is pressed
- Release the video capture and close all OpenCV windows
