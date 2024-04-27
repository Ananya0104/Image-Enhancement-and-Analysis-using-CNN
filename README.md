# Image-Enhancement-and-Analysis-using-CNN
Analysing edge detection, sharpening, and noise reduction and Effects of changing strides on images and how it alters their properties and appearance

Edge Detection:
Why we use it: Edge detection is a fundamental image processing technique used to identify boundaries within an image. It's crucial for tasks like object detection, image segmentation, and feature extraction.
What we expect: By performing edge detection, we anticipate to highlight significant transitions in intensity, which correspond to edges or boundaries in the image. The result should be a binary image or a map indicating the presence of edges
# Original Image
<img width="660" alt="Screenshot 2024-04-27 at 6 39 11 PM" src="https://github.com/Ananya0104/Image-Enhancement-and-Analysis-using-CNN/assets/120671151/1c2ca8bd-95a9-4dc3-8cf0-a34056c8e9ef">
# After Edge Detection Technique
<img width="659" alt="Screenshot 2024-04-27 at 6 39 38 PM" src="https://github.com/Ananya0104/Image-Enhancement-and-Analysis-using-CNN/assets/120671151/d9ec2131-28f4-4ec2-a763-cd91b65b9510">

Sharpening:
Why we use it: Sharpening enhances the edges and details in an image, making it appear clearer and more defined. It's often used to improve the visual quality of images.
What we expect: When we apply sharpening, we anticipate that edges and details in the image will become more pronounced. The result should be an image with enhanced contrast along edges and finer details.

Noise Reduction:
Why we use it: Noise reduction is employed to remove or reduce unwanted artifacts or distortions in an image caused by various sources such as sensor noise, compression, or environmental factors.
What we expect: The goal of noise reduction is to smoothen the image while preserving important details and structures. We expect that after noise reduction, the image will have a cleaner appearance with reduced graininess or speckles.

Effects of Changing Strides on Images:
Why we study it: Changing the stride during image processing operations like convolution or pooling alters the sampling rate and affects the spatial dimensions of the output.
What we expect: Altering the stride can lead to changes in the properties and appearance of the resulting image. For example, increasing the stride may reduce the spatial resolution and processing time but can also lead to loss of information. Decreasing the stride may enhance spatial resolution but may require more computational resources.
In summary, each of these image processing techniques serves specific purposes and is employed to achieve desired outcomes. Understanding their effects and how they alter image properties and appearance is crucial for making informed decisions in various applications such as computer vision, image enhancement, and feature extraction.
