The aim of this project is to use TensorFlow and the Transformers library to fine-tune a pre-trained natural language processing model. Specifically, we will use the DistilBERT model to classify text as either spam or ham (not spam) based on the SMS Spam Collection dataset. We will demonstrate how to tokenize and encode the text data, build and train the model, and evaluate its performance using metrics such as accuracy. By the end of this tutorial, we will save the model and try to predict a new text into ham or spam. We will also do Exploratory Data Analysis and cleaning on the dataset. 

Our first choice was to use SST (Stanford Sentiment Treebank) dataset. We had downloaded the text file and had converted it onto csv, did exploratory analysis and cleaning, and other steps of fine tuning, however the tuning part was taking too much time even on GPU ( more than 2 hours) and still was under the tuning process, and due to the lack of time we had to switch to a smaller and easier dataset for this project. Hence, we chose ham and spam dataset. 



