Motion Detection with OpenCV

This Python script implements a basic motion detection system using OpenCV. It captures video from the webcam, processes each frame to detect motion, and highlights the areas where motion is detected.


Key Features:

1)Webcam Capture: Continuously captures frames from the webcam.

2)Frame Processing: Converts frames to grayscale and applies Gaussian blur to reduce noise and detail.

3)Background Subtraction: Uses the first frame as the reference background and calculates the difference with the current frame.

4)Thresholding and Dilation: Applies thresholding to highlight significant differences and dilates the result to fill in gaps.

5)Contour Detection: Finds contours of the thresholded differences to identify areas of motion.

6)Motion Highlighting: Draws bounding boxes around the detected motion areas and displays a message indicating motion detection.

7)User Interaction: Allows the user to exit the loop and close the window by pressing the 'q' key.
