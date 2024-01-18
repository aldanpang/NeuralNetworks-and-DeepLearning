Final Project done for SC4001 Neural Networks and Deep Learning

Experimenting with applying Self-Attention mechanism to Recurrent Convolutional Neural Network for recognising emotions from corpus of texts - specifically tweets from Twitter.
This method was chosen with the goal of creating a model that understands the context of an entire sentence before assigning emotions to words.

RNN and CNN are combined, to:
1) Take advantage of RNN's recurrent structure for preserving longer contextual information while introducing less noise
2) Using max-pooling layer from CNNs to select more discriminative features and capturing contextual information through convolutional layer

As RCNN models have been experimented with before for text emotion recognition, we decided on adding self-attention mechanism adopted from Transformers in our model.

Our final train loss obtained was 1.990.
