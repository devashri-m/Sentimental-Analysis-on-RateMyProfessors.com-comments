# Sentimental-Analysis-on-RateMyProfessors.com-comments

**Datasets:** <br>
**Embeddings:** <br>
While you are welcome to attempt to represent words using one-hot encoding, your analysis is likely to be significantly more effective with a word embedding. While you are welcome to train your own Embedding layer in Keras or PyTorch, you will probably want to use a pre-trained embedding like GloVe.
To use GloVe from Keras see Using pre-trained word embeddings in the Keras examples.
Note: Do not use wget and unzip to download the embeddings each time as shown in the example. Upload a copy to Google Drive, or save and reload the model once the embedding layer has been created.
To use GloVe from PyTorch, see the Pretrained Word Embeddings in the torchtext.vocab module.
Alternatively, you might use a third-party library like Gensim.
Comments and ratings
In addition to leaving comments on Rate My Professors, reviews also include scores for “Quality” and “Difficulty.” There are at least two publicly-available datasets that include this information:<br>
●	A larger dataset in CSV format from Dr. Hibo Je at Tsinghua University.<br>
●	A smaller dataset in JSON format from Kaggle containing reviews from the undergraduate Claremont Colleges.<br>
You may also wish to use additional data for training, whether through data augmentation, by contacting Dr. He for his full dataset, or experimenting with web scraping code.
**Task:**
Your task is to use a recurrent neural network model to predict the quality and difficulty scores that a student will assign, given the text of the student’s comments.
You are free to use any appropriate RNN architecture, and are welcome to attempt transfer learning with a pre-trained model upstream. To get started, see the Keras tutorial Text classification with an RNN or Text classification with the torchtext library.

