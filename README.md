# Image_Caption_Generator_Using_Deep_Learning
Image_Caption_Generator_Using_Deep_Learning

Image Caption Generator Using Deep Learning on Flickr8K Dataset

The Image Caption Generator is a deep learning project that aims to generate descriptive captions for images using the Flickr8K dataset. This project leveragesConvolutional Neural Networks (CNN) for image feature extraction and Recurrent Neural Networks (RNN) with Long Short-Term Memory (LSTM) units forgenerating sequences of words. The Flickr8K dataset, which consists of 8,000 images each paired with five different captions, is used to train the model. Theprocess involves preprocessing images and captions, creating embeddings, and training the model to map image features to natural language descriptions. Thisresults in a model capable of generating accurate and contextually relevant captions for new images.


Libraries used:
The project uses `pandas` and `numpy` for data manipulation, `re` for regular expressions, `keras.preprocessing.image` for image preprocessing, `matplotlib.pyplot` for plotting, `keras.applications.resnet50` for ResNet50 model and preprocessing, `keras.models` for creating models, `keras.layers` for defining layers, `keras.preprocessing.sequence` for sequence preprocessing, and `keras.utils` for utility functions like `to_categorical`.
