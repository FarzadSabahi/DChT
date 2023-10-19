# Discrete Chebyshev Transform for Images

This repository contains a Python script that performs a Discrete Chebyshev Transform on images. The Chebyshev Transform is a mathematical transformation that can be applied to data (like Fourier or Cosine Transforms) and can be useful in various signal processing applications.
Getting Started
Prerequisites

### You will need the following Python libraries:

    numpy
    OpenCV (cv2)
    matplotlib

You can install these libraries using pip:

pip install numpy opencv-python matplotlib

### How the code works

__chebyshev_poly(n, x)__: This function computes the nth Chebyshev polynomial of the first kind for a given x.

__discrete_chebyshev_transform_1d(sequence, n):__ Computes the 1D Discrete Chebyshev Transform for a given sequence.

__discrete_chebyshev_transform_2d(image):__ Computes the 2D Discrete Chebyshev Transform for an image. This is the main function used for transforming our image data.

__Image Loading:__ The script reads a grayscale image ('input1.jpg').

__Transform Application:__ The 2D Discrete Chebyshev Transform is applied to the loaded image. The resultant coefficients can have extreme values. To visualize them effectively, the coefficients are clipped to remove outliers and then normalized.

__Visualization:__ The processed coefficients are displayed using matplotlib.

### Usage

Ensure you have an image named input1.jpg in the same directory as the script.
Run the Python script. If using the command line:
python filename.py

#### Contributing
Feel free to fork the repository, make your changes, and submit a pull request. Any contributions to enhance the functionality or improve the code are welcome!
