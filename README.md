# Image-Caption-Generator

This project demonstrates the creation of an Image Caption Generator using deep learning techniques. The code is structured as follows:

Data Preprocessing: Image features are extracted using a pre-trained VGG16 model. Captions are cleaned and tokenized, and train-test split is performed.

Model Architecture: The model comprises an encoder and a decoder. The encoder processes image features, and the decoder generates captions using LSTMs.

Training: The model is trained using a data generator, and two different models are provided for improved accuracy.

Caption Generation: You can use the trained model to generate captions for input images.

Evaluation: The quality of generated captions can be evaluated using BLEU scores.

Visualization: The code includes functions for visualizing actual and predicted captions for sample images.

This project showcases the use of deep learning to generate meaningful and contextually relevant captions for images.
