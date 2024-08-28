Automated Document Alignment and Enhancement

This Python script uses OpenCV, NumPy, and Matplotlib to automate the process of aligning and enhancing scanned documents. 

The script utilizes the following techniques:

ORB Feature Detection : Detects features in two images (im1 and im2) using the Oriented FAST and Rotated BRIEF (ORB) algorithm.

DrawMatches : Draws the matches found between the two images, highlighting any discrepancies or misalignments.

Homography Estimation : Estimates the homography matrix that best aligns the two images using RANSAC-based estimation.

After the image aligned I use several steps as:

Image Cropping : Crops the aligned image to remove any borders or unnecessary areas.

Brightness Enhancement : Boosts the brightness of the cropped and aligned image to improve visibility.

Adaptive threshold : for next step to doing character recognition
