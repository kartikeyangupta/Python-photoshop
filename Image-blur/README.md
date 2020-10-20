# Image Blurring
Image blurring is achieved by convolving the image with a low-pass filter kernel. It is useful for removing noise. It actually removes high frequency content (e.g: noise, edges) from the image resulting in edges being blurred when this is filter is applied.

# Averaging
This is done by convolving the image with a normalized box filter. It simply takes the average of all the pixels under kernel area and replaces the central element with this average. This is done by the function cv2.blur() or cv2.boxFilter(). Check the docs for more details about the kernel. We should specify the width and height of kernel.

A 3x3 normalized box filter would look like this:
K = 1/9 [1 1 1, 1 1 1, 1 1 1]

# Steps to be followed to run script:
1. Copy the script in your code
2. Replace 'Original.jpg' with your image file name
3. Download required packages (stated in Requirement.txt)
4. Run the code
