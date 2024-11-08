# Image Processing Techniques

This repository contains Python implementations for various **Image Processing** techniques that focus on **Image Compression** and **Morphological Image Processing**. These methods are part of a school project in the **Image Processing and Computer Vision** class.

## Features

### Image Compression
- **Lossless Compression**: Reduces the file size of an image without any loss of quality. This technique retains all image details after compression.
- **Lossy Compression**: Compresses the image by sacrificing some quality to achieve higher compression ratios. Ideal for situations where minor quality loss is acceptable.

### Morphological Image Processing
- **Erosion**: Shrinks or reduces the boundaries of objects within the image.
- **Dilation**: Expands or grows the boundaries of objects in an image.
- **Opening**: A combination of erosion followed by dilation, used to remove noise and small objects from an image.
- **Closing**: A combination of dilation followed by erosion, useful for filling small holes and gaps in objects.

## Technologies Used
- **Python**: The primary language used for implementing image processing techniques.
- **OpenCV**: A widely-used library for real-time computer vision tasks, including image transformations.
- **NumPy**: For numerical operations on images (such as matrix manipulations).

