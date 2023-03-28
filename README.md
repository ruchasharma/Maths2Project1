# Maths2Project1

Ham Spam Message Classification using Transformers
This project aims to classify text messages as either ham or spam using a pre-trained Transformer model from the Hugging Face Transformers library. The model is fine-tuned on a dataset of labeled messages and evaluated for accuracy. The project is implemented in Python using TensorFlow and the Hugging Face Transformers library.

Dataset:

The dataset used for training and evaluation is the well-known SMS Spam Collection Dataset from Kaggle. It contains a collection of SMS messages tagged as either ham or spam.

Pre-processing:

The text messages are pre-processed using the transformers library. The messages are tokenized and encoded using the DistilBertTokenizer from the Transformers library. The encoded messages are then padded to a fixed length and converted to TensorFlow Dataset objects.

Model:

The pre-trained DistilBert model from the Hugging Face Transformers library is used as the base model. The model is fine-tuned on the pre-processed dataset using the TFTrainer class from the transformers library.

Evaluation:

The trained model is evaluated on a separate test dataset. The evaluation metric used is accuracy. The accuracy of the model on the test dataset is printed at the end of the training process.

Requirements:

The project requires the following packages to be installed:

transformers
tensorflow
matplotlib
wordcloud

Conclusion:

In this project, we demonstrated how to use a pre-trained Transformer model to classify text messages as ham or spam. The use of the Hugging Face Transformers library made the implementation of the project easy and straightforward. The model achieved a high accuracy on the test dataset, indicating its effectiveness in classifying text messages. The key takeaway from this project is that pre-trained Transformer models can be easily fine-tuned on a specific dataset to achieve high accuracy in text classification tasks.



