# Introduction to Image_Processing:
# Image:
Image is a digital representation of a visual scene, expressed in a two-dimensional(Gray-scale) or three-dimensional(RGB) arry of numerical values called pixels, Each pixel corresponds to a specific location in the image and carries information about the light intensity. In case of color images, multiple channels such as red, green, and blue (RGB) form an RGB image. We can think of an image as matrix of intensity values.
. Grey-Scale Images: Grey scale images are easier to understand. They can be represented in a 2D matrix, each entry representing the brightness, ranging from 0 (black) to 255 (white).
. Color Image: A color iamge is a 3D tensor where each pixel has multiple channels Red, Green and Blue intensities that add up to produce the full spectrum of colors as shown in the above figure also.
. Higher-dimensional images: In specialized domains (e.g., medical imaging, hyperspectral imaging), an image can have more than three channels, each representing different spectral or physical properties.
# Image Processing
Definition: The manipulation and analysis of digital images to enhance quality, extract information, or transform them for further analysis. This is the foundation of computer vision.
Real-life example: When you apply filters on Instagram or adjust brightness/contrast on your phone photos, you're doing basic image processing. Medical X-rays are often enhanced using image processing to make fractures more visible.
