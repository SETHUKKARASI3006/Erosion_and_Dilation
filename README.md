# Erosion_and_Dilation

This project implements the fundamental morphological operations of **Erosion** and **Dilation** on digital images. These techniques are crucial for various image processing tasks, including noise reduction, feature extraction, and image segmentation.

### Project Goal

The primary objective is to provide a clear, functional implementation of:

  * **Erosion:** Shrinks or thins objects in a binary image.
  * **Dilation:** Grows or thickens objects in a binary image.

The code is designed to demonstrate how a **Structuring Element (Kernel)** is used to probe and modify the image pixels to achieve these effects.

### Technologies Used

  * **Language:** Python
  * **Libraries:**
      * `NumPy`: For efficient array manipulation (image representation).
      * `OpenCV (cv2)`: For image reading, writing, and displaying results.

### Getting Started

To run this project, you need Python and the necessary libraries installed.

#### Prerequisites

```
pip install numpy opencv-python
```

#### Running the Script

1.  Clone the repository:
    ```
    git clone https://github.com/SETHUKKARASI3006/Erosion_and_Dilation.git
    cd Erosion_and_Dilation
    ```
2.  Create a input image using numpy

### Expected Output

The script will typically display or save two output images:

1.  The image processed with **Erosion**.
2.  The image processed with **Dilation**.

-----
