# CNN_Colab
This is repo to store my all Google Colab file for CNN & Image Augmentatin
****************************************************************************************
****************************************************************************************
CNN is used to classify Image.


# ***Create the convolutional base***
****************************************************************************************
****************************************************************************************

The 6 lines of code below define the convolutional base using a common pattern: a stack of Conv2D and MaxPooling2D layers.

As input, a CNN takes tensors of shape (image_height, image_width, color_channels), ignoring the batch size. If you are new to these dimensions, color_channels refers to (R,G,B). In this example, you will configure our CNN to process inputs of shape (32, 32, 3), which is the format of CIFAR images. You can do this by passing the argument input_shape to our first layer.
