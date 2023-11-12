# Neural-Style-Transfer

This notebook implements Neural Style Transfer, a technique to apply the artistic style of one image to the content of another image. The project is built using Python 3.7.16 and TensorFlow 1.15.0, with VGG19 as the chosen Convolutional Neural Network (CNN) model. The optimization process utilizes the L-BFGS optimizer. The pretrained VGG19 model is used to extract features from the style image and then L-BFGS optimizer is used for the imposition of these features onto the content image.

## Getting Started

### Prerequisites

- Python 3.7.16
- TensorFlow 1.15.0
- Scipy 1.2.0
- numpy
- skimage
- matplotlib
- pandas

It's recommended to use a virtual environment to manage dependencies. The virtual environment should have python 3.7, the tensorflow version 1.x.x and scipy version 1.2.0.  
Clone this repository to your local machine.
Run the python file on the virtual environment you created. Import all the important dependencies. 
Upload the style image containing the style you want to impose on the content image, in you working directory and change the style path and content path accordingly.

## Result








