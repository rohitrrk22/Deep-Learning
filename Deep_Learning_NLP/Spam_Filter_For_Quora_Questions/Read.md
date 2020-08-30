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
  Following Table shows the number of questions each models with different pretrained embeddings were correctly able to classify as Spam & Non-Spam.
  
  ![Confusion Matrix of Different Pretrained Models](https://github.com/rohitrrk22/Deep-Learning/blob/master/Deep_Learning_NLP/Spam_Filter_For_Quora_Questions/Images/Confusion_Matrix.PNG)

  
  

## Tested On:
* [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb)
