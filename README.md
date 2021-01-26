Detecting Lanes on road

This project uses computer vision method for detecting lanes on the road. cv2 and numpy libraries are used to process and filter the image which was further used to detect lanes marked on the road. Following steps were followed:
Decoding captured video: Convering the captured video in the sequence of images.
Grayscale conversion of image: The images are coverted from RGB format to grayscale.
Reduce noise: Gaussian filter is used to reduce the noise.
Canny Edge Detector: Computing the edges and area with high intensity in the image.
Region of Interest: removing the contour of the image which is not useful for detecting lanes. For example, keeping only road in the frame.
Hough Line Transform: It is used to transform the high intensity pixels in the image to lines.
