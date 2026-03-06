This notebook demonstrates different image enhancement and preprocessing techniques using Python, OpenCV, NumPy, and Matplotlib. The purpose of the project is to improve image quality in different real-world scenarios such as medical images, satellite images, scanned documents, surveillance frames, and foggy road images.

Added Features:-

The notebook includes multiple image enhancement techniques:

Image Upload Feature:
Users can upload images directly using the files.upload() function in Google Colab.

Grayscale Conversion:
Images are converted to grayscale when required for processing.

Histogram Equalization:
Improves contrast in low-contrast images by redistributing intensity values.

CLAHE (Contrast Limited Adaptive Histogram Equalization):
Enhances local contrast while preventing noise amplification.

Contrast Stretching:
Expands the intensity range of an image to make details more visible.

Image Enhancement for Different Scenarios:

Low-contrast X-ray images

Satellite images

Low-light surveillance frames

Scanned documents

Foggy road images

Visualization:
Original and enhanced images are displayed using Matplotlib for comparison.

Navigation Flow:

Run the notebook cell by cell from top to bottom.

Each section will prompt the user to upload an image.

After uploading, the notebook:

Reads the image using OpenCV

Applies the specific enhancement technique

Displays the original and processed results.

Each block focuses on a different image processing technique or use case.

Technologies Used:

Python

OpenCV (cv2)

NumPy

Matplotlib

Google Colab file upload interface
