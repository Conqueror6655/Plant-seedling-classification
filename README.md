# Plant-seedling-classification
In this project, we are using deep learning convolution neural network algorithms to classify plant seedlings. The dataset is available on Kaggle.

I have added 2 different submission files that has output for 2 different models

# Introduction:-
In the dataset, we have different 12 classes of seedlings under train dataset. In particular, we will focus on the parameters and preprocess the parameters before training our model. In modeling, we will use different image processing algorithms such as Convolutional Neural Network, ResNet ,VGG-16. Initially, there are unwanted background noise in the images, we have used various image processing techniques like: segmentation, masking and sharpening to handle this situation. Plant seedling classification is the primary step towards this process. It will help to classify the required seedlings between the weeds and encouraging nutrient, pesticide or medicinal items to be added in timely manner.

# Image preprocessing:-

To begin with, we need to remove background image and focus on leaves. The masking principle is also called spatial filtration.
Image segments are a widely used method in digital photography and analysis, which is often based on the properties of the image pixels to partition an image into different sections or areas. Image segmentation can be based on color or shaped resemblance, distinguishing the foreground from the background or clusters pixel areas.
Image sharpening refers to a technology for improving the boundaries and fine details in a photo. Picture sharpening is commonly employed for increasing local contrast and sharpening photos in printing and photographs sectors. In general, sharpening of the image consists of inserting a signal equal to the original image in a high-pass filtered version.

# Models:-

Convolution Neural Network (CNN)
Convolutions neural networks (CNN or ConvNets) is one of the major classifications of objects. The identification of objects, reconnaissance faces etc. are some of the fields of frequent use for CNNs. CNNs have two major elements. 1. Learning features: Transforming, ReLU, Layer pooling stages. In this function learning phase edges, colours, lines and curves are extracted. 2. Classification: In this process, you can find the Fully Connected(FC) layer. They assign a chance to what the algorithm says for the object in the image.

VGG16
VGG16 is a CNN architecture used in 2014 for winning the ILSVR(Imagenet) competition. It has until now been considered one of the most impressive model architectures. The most unusual aspect of VGG16 is that they insisted on making 3x3 philtre layers, with a phase 1, and still used the same 2x2 string filter padding and max-pool layer. The entire architecture is constantly assisted by this arrangement of convolutions and max pool layers. At last, the softmax for the production is 2 FC (fully linked layers). The sixteenth in VGG16 corresponds to a weight of 16 layers.
