# Spam Filter for Quora Questions using Transfer Learning

       A Spam Question Classifier for Quora Questions using pretrained embeddings like Glove,Bert,Word2Vec & FastText. 
    
## Requirements:
* TensorFlow 2.x
* NLTK
* Punkt Sentence Tokenizer from NLTK
* [Glove Pretrained Embeddings](https://nlp.stanford.edu/projects/glove/)
* [Word2Vec Pretrained Embeddings](http://vectors.nlpl.eu/repository/)
* [FastText Pretrained Embeddings](https://fasttext.cc/docs/en/english-vectors.html)
* [Bert Pretrained Embeddings](https://github.com/google-research/bert)


## Performance of Different Pretrained Models:

The Following Table shows the performance of the models on the basis of Accuracy and ROC AUC Score. 
![Performance of Different Pretrained Models](https://github.com/rohitrrk22/Deep-Learning/blob/master/Deep_Learning_NLP/Spam_Filter_For_Quora_Questions/Images/Performance.PNG)

## Confusion Matrix Observations:

The Following table shows the number of questions each models with different pretrained embeddings were correctly able to classify as Spam & Non-Spam.

![Confusion Matrix of Different Pretrained Models](https://github.com/rohitrrk22/Deep-Learning/blob/master/Deep_Learning_NLP/Spam_Filter_For_Quora_Questions/Images/Confusion_Matrix.PNG)

## Observations and Conclusion:

* As per the observation from the performance table,the accuracy of all the models on both the train and test dataset looks quite similar but on the basis of ROC AUC Score we can say that the model with "Bert" embedding performs poorly as compared to other three models.
* Since as per the performance table models with Glove,FastText & Word2Vec pretrained embeddings performance almost similarly we need to check how these models classify the two classes for which we need to observe the Confusion Matrix Table.
* By observing the Confusion Matrix Table we can see how each model classifies both the classes as compared to actual questions for both classes as 15991 of Spam Questions and 245234 of Non-Spam Question.
* On the basis of the Confusion Matrix Table we can say that the model with "Glove" pretrained embedding performs the best among all as it correctly classifies most of the questions as Spam & Non-Spam while model with "Bert" pretrained embeddings performs the worst as it classifies all the questions as Non-Spam Questions.
* On the basis of above observations we can conclude that the model with "Glove" pretrained embeddings is the best suitable for the Quora Spam Filter Classifier Use Case.

## Usage:
```
SpamFilter_GLOVE_Final.ipynb
FastText.ipynb
Word2Vec.ipynb
SpamFilter_Bert_Embedding.ipynb
```


  
  

## Tested On:
* [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb)



## Acknowledgment:
1. [Glove](https://nlp.stanford.edu/projects/glove/)
2. [Word2Vec](http://vectors.nlpl.eu/repository/)
3. [FastText](https://fasttext.cc/docs/en/english-vectors.html)
4. [Bert](https://github.com/google-research/bert)



