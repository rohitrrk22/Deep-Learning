# Spam Filter for Quora Questions using Transfer Learning

       A Spam Question Classifier for Quora Questions using pretrained embedding like Glove,Bert,Word2Vec & FastText. 
    
## Requirements:
* TensorFlow 2.x
* NLTK
* Punkt Sentence Tokenizer from NLTK
* [Glove Pretrained Embeddings](https://nlp.stanford.edu/projects/glove/)
* [Word2Vec Pretrained Embeddings](http://vectors.nlpl.eu/repository/)
* [FastText Pretrained Embeddings](https://fasttext.cc/docs/en/english-vectors.html)
* [Bert Pretrained Embeddings](https://github.com/google-research/bert)


## Performance of Different Pretrained Models:

![Performance of Different Pretrained Models](https://github.com/rohitrrk22/Deep-Learning/blob/master/Deep_Learning_NLP/Spam_Filter_For_Quora_Questions/Images/Performance.PNG)

* Confusion Matrix Observations:
  * Glove: 
    Model with Pretrained Glove Embedding correctly classifies 10716 Questions as Spam and 239305 Questions as Not Spam.
  * FastText: 
    Model with Pretrained FastText Embedding correctly classifies 8121 Questions as Spam and 242210 Questions as Not Spam.
  * Word2Vec: 
    Model with Pretrained Word2Vec Embedding correctly classifies 3452 Questions as Spam and 243612 Questions as Not Spam.
  * Bert: 
    Model with Pretrained Bert Embedding correctly classifies 0 Questions as Spam and 245234 Questions as Not Spam.

  

## Tested On:
* [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb)
