# OpenCV_Coursera_Project
Coursera OpenCV mini-Project
You can find the Coursera project [here](https://www.coursera.org/projects/computer-vision-opencv-for-images).

# Image Processing with OpenCV and Pillow

This Python code demonstrates various image processing techniques using the OpenCV and Pillow (PIL) libraries. It loads an image, performs operations like color channel manipulation, resizing, drawing shapes, and text annotation, and displays the results using Matplotlib.

## Getting Started

### Prerequisites

- Python
- OpenCV (`cv2`)
- Pillow (`PIL`)
- Matplotlib

You can install the required Python packages using pip:

```bash
pip install opencv-python-headless pillow matplotlib

## Code Explanation

- The code begins by loading an image using Pillow (`PIL`) and then converting it into a NumPy array for further manipulation.

- Various operations on color channels are demonstrated, including displaying individual color channels and converting them to grayscale.

- OpenCV (`cv2`) is introduced for image processing tasks, such as loading images (which are initially read as BGR), fixing color channel order, loading images in grayscale, and resizing images.

- The code showcases how to draw shapes (circles, rectangles, lines) on images using OpenCV and how to add text annotations.

- The resulting images are displayed using Matplotlib.
