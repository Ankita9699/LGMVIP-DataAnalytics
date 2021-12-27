Task-2 :- Image to Pencil Sketch with Python

Description :-

We need to read the image in RBG format and then convert it to a grayscale image. This will turn an image into classic black and white photo. Then the next thing to do is invert the grayscale image also called negative image, this will our inverted grayscale image. Inversion can be used to enhance details. Then we can finally create the pencil sketch by mixing the grayscale image with the inverted blurry image. This can be done by dividing the grayscale image by the inverted blurry image. Since images are just arrays, we can easily do this programmatically using the divide function from the cv2 library in Python.

Implementation:-

Step 1: Importing the OpenCV [cv2] library

Step 2: Load the Image in OpenCv (cv2)

Step 3: Convert Image to RBG format

Step 4: Convert RGB Image to Grayscale format

Step 5: Convert RGB Image to LUV format

Step 6: Now Invert the Grayscale image [ Convert Grayscale to Negative format ]

Step 7: Blur the Image using Gaussian Function in OpenCV

Step 8: Convert to Pencil Sketch Image

Step 9: Original v/s Pencil Sketch

Result:-

Accuracy of Image to Pencil Sketch with Python:- 98%
Accuracy of Image to Pencil Sketch with Python:- 100%

Thank you!!!
