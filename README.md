# Object-detection-and-Classification
The object detection and classification using custom CNN that is made up of convolution and pooling layers.
you'll build a CNN from scratch to:

# classify the main subject in an image
# localize it by drawing bounding boxes around it.

# Define the Networ


# Here, you'll define your custom CNN.

# feature_extractor: these convolutional layers extract the features of the image.
# classifier: This define the output layer that predicts among 10 categories (digits 0 through 9)
# bounding_box_regression: This defines the output layer that predicts 4 numeric values, which define the coordinates of the bounding box (xmin, ymin, xmax, ymax)
# final_model: This combines the layers for feature extraction, classification and bounding box prediction.
# Notice that this is another example of a branching model, because the model splits to produce two kinds of output (a category and set of numbers).
# Since you've learned to use the Functional API earlier in the specialization (course 1), you have the flexibility to define this kind of branching model!
# define_and_compile_model: choose the optimizer and metrics, then compile the model.


# Get and prepare the model
# You'll be using the InceptionV3 model.

# Since you're making use of transfer learning, you'll load the pre-trained weights of the model.
# You'll also freeze the existing layers so that they aren't trained on your downstream task with the cats and dogs data.
# You'll also get a reference to the last layer, 'mixed7' because you'll add some layers after this last layer.
