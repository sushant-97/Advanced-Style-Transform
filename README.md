# Style-Transform
Dashtoon Placement Assignment Submission

Neural Style Transfer (NST) stands out as a captivating image stylization method rooted in Deep Learning, enabling the creation of artistic pieces through machine learning. The essence of NST lies in transforming a content image to adopt the stylistic characteristics of a chosen style image. When we delve into the notion of "style" in an image, we are referring to its texture, brush strokes, geometric shapes, and the spatial distribution of colors.

Contrary to a straightforward image overlay process, NST introduces a nuanced approach to image stylization. It distinguishes itself from mere image overlaying, which involves placing one image atop another without any stylistic transformation. To illustrate this disparity, consider Figure 2: (a) depicts the outcome of image overlaying, while (b) showcases the result of image stylization. This visual comparison aims to elucidate the contrasting nature of these two processes.

Now, let's explore the sequential steps involved in NST:

STEP 1: Choose the Content and Style Image.
Select the images that will serve as the content and style references for the stylization process.

STEP 2: Preprocess the Image.
Prepare the chosen images for further processing by applying necessary transformations.

STEP 3: Generate a Random Image.
Create an initial image of the same dimensions as the content and style images.

STEP 4: Design the Model.
Establish the neural network architecture that will facilitate the style transfer.

STEP 5: Calculate Loss.
Define and compute the loss function, representing the difference between the generated image and the desired stylized output.

STEP 6: Optimize Until Converged.
Iteratively adjust the generated image to minimize the calculated loss, optimizing until convergence is achieved.

These six steps encapsulate the essence of NST implementation. While the process may sound straightforward, the underlying complexities become evident when delving into the detailed coding aspects. For the purposes of this implementation, Google Colab has been employed to execute and experiment with the provided code.
