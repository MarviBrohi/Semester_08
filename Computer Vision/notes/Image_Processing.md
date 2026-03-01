# Introduction to Image_Processing:
# Image:
Image is a digital representation of a visual scene, expressed in a two-dimensional(Gray-scale) or three-dimensional(RGB) arry of numerical values called pixels, Each pixel corresponds to a specific location in the image and carries information about the light intensity. In case of color images, multiple channels such as red, green, and blue (RGB) form an RGB image. We can think of an image as matrix of intensity values.
. Grey-Scale Images: Grey scale images are easier to understand. They can be represented in a 2D matrix, each entry representing the brightness, ranging from 0 (black) to 255 (white).
. Color Image: A color iamge is a 3D tensor where each pixel has multiple channels Red, Green and Blue intensities that add up to produce the full spectrum of colors as shown in the above figure also.
. Higher-dimensional images: In specialized domains (e.g., medical imaging, hyperspectral imaging), an image can have more than three channels, each representing different spectral or physical properties.
# Image Processing
Definition: The manipulation and analysis of digital images to enhance quality, extract information, or transform them for further analysis. This is the foundation of computer vision.
Real-life example: When you apply filters on Instagram or adjust brightness/contrast on your phone photos, you're doing basic image processing. Medical X-rays are often enhanced using image processing to make fractures more visible.
. Grey-Scale Images: Grey scale images are easier to understand. They can be represented in a 2D matrix, each entry representing the brightness, ranging from 0 (black) to 255 (white).
. Color Image: A color iamge is a 3D tensor where each pixel has multiple channels Red, Green and Blue intensities that add up to produce the full spectrum of colors as shown in the above figure also.
. Higher-dimensional images: In specialized domains (e.g., medical imaging, hyperspectral imaging), an image can have more than three channels, each representing different spectral or physical properties.
# Types of Image Processing
. Visualization: Find objects that are not visible in the image.
. Recognition: Distinguish or detect objects in the image.
. Sharpening and restoration: Create an enhanced images from the original image.
. Pattern recognition: Measure the various patterns around the objects in the image.
. Retrieval: Browse and search images from a large database of digital images that are similar to the original image.
# Image Transformation:
It is the process of converting an image from one form or representation to another to improve visual quality, extract meaningful information, or prepare it for further analysis.
# Image Filter: 
In image processing different filters are used to modify or enhance the appearance of an image by manipulating the values of its pixels. It involves applying a mathematical operation to each pixel in the image. At each position, the kernel (or filter) combines the values of neighbouring pixels with specific weights, producing a new value for the central pixel. This allows filters to extract and highlight certain features of an image or suppress unwanted information. This process used in applying filters on pixels is called convolution, explained below:
# 1:Input Image:
You start with an original image, which is a grid of pixels, each with a specific color or intensity value.
# 2:Filter Kernel (Convolution Matrix):
A filter works by taking a small matrix, known as a window, kernel or mask. It is also called a convolution matrix. This is a small matrix of numbers that defines the operation to be performed. Different kernels produce different filtering effects.
# 3:Convolution Operation:
The filter kernel is then “convolved” with the image. This involves:
. Placing the center of the kernel over a pixel in the input image.
. Multiplying each element of the kernel with the corresponding pixel value in the image region it covers.
. Summing up all these products.
This sum becomes the new value for the center pixel in the output (filtered) image.
. This process is repeated for every pixel in the input image.
# Edge Handling:
When the kernel is at the edges of the image, some of its elements might fall outside the image boundaries. Various methods are used to handle this, such as:
. Padding: Adding extra rows and columns of pixels around the image (e.g., with zeros, replicated edge pixels, or mirrored pixels).
. Cropping: Simply not processing the edge pixels where the kernel goes out of bounds.
# Output Image:
The result of the convolution operation is a new image where each pixel’s value has been transformed according to the filter.
Real-Life-Example: The "Portrait mode" on smartphones uses filtering to blur the background(bokeh effect) while keeping the subject in focus. Another example is noice reduction in low-light photos.
