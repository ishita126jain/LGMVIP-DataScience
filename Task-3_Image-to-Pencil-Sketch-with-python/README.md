# LetsGrowMore_Task-3_Image-to-Pencil-Sketch-with-python
The basic idea behind converting an image to a pencil sketch is to create a gray-scale version of the image and then apply some filters to create a sketch-like effect. Here is a high-level overview of the process:

Load the input image using a Python image library like Pillow or OpenCV.

Convert the image to grayscale using a suitable function.

Invert the grayscale image using the bitwise_not() function from the cv2 library.

Apply a Gaussian blur to the inverted grayscale image to smoothen the edges using the GaussianBlur() function.

Blend the blurred image with the original grayscale image using the dodge() function.

Adjust the brightness and contrast of the final image to get the desired effect.

Save the final image using the imwrite() function.
