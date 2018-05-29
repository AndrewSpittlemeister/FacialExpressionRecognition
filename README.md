# FacialExpressionRecognition

- Using Kaggle's fer2013 data set.
- Using Keras with a tensorflow backend.
- Notebooks are executed in Google's Collaboratory Environment (Python3 with Tesla K80 GPU support).

  This project consists classifying the facial expressions of a human present in an input image to evaluate emotional effects of social media and offer some control over its progression. Classification was accomplished through training a three-phase deep convolutional neural network (CNN)  on a dataset of 32,298 pre-cropped grayscale images of human faces exhibiting 1 of 7 facial expressions. Various levels of the CNN represent the extraction of different features relevant to the problem; this feature data is flattened and fed into a densely connected deep neural network to perform classification of the facial expression.  We show that our three-phase CNN delivers accurate predictions of up to 53% on a validation set of 3,589 sample images. This trained network plays a key role in an agent that uses this predicted information on the user’s facial expression to yield a specific social media experience.
