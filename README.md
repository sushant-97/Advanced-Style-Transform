# Style-Transform - Dashtoon Placement Assignment Submission

dataset and final fine-tuned model can be found on [gdrive](https://drive.google.com/drive/folders/1786Mci_dJST0vgzm0Wd3O0WWThmBIx-p?usp=sharing)

## Requirements

- Python 3.7
- PyTorch 1.0+
- TorchVision
- Pillow
- Skimage
- tqdm

Anaconda environment recommended here!

(optional)

- GPU environment for training


## Overview
Neural Style Transfer (NST) is a captivating image stylization method rooted in Deep Learning, enabling the creation of artistic pieces through machine learning.

- NST transforms a content image to adopt the stylistic characteristics of a chosen style image.
- It goes beyond simple image overlaying, incorporating nuances such as texture, brush strokes, geometric shapes, and color distribution.

## Visual Comparison
![Image Overlay vs NST](images/sample_1.gfg)
- (a) Image Overlay
- (b) NST Result

![Image Overlay vs NST](images/sample_2.gfg)
- (a) Image Overlay
- (b) NST Result

## Steps Involved in NST
1. **Choose Content and Style Image:** Select content and style images for stylization.
2. **Preprocess Image:** Apply necessary transformations to prepare images.
3. **Generate a Random Image:** Create an initial image of the same dimensions.
4. **Design the Model:** Establish the neural network architecture.
5. **Calculate Loss:** Define and compute the loss function.
6. **Optimize Until Converged:** Adjust the image iteratively to minimize the loss.

## Implementation Details
- Google Colab has been used for execution and experimentation with the provided code.

