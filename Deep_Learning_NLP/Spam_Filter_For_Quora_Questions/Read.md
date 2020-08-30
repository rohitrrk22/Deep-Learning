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

## Tested On:
* [Google Colab](https://colab.research.google.com/notebooks/intro.ipynb)

## Performance of Different Pretrained Models:

|              | Train | Test |
| :---         |     :---:      |          ---: |
| Different Pretrained Models | Accuracy | Accuracy | ROC AUC Score |
| --- | --- | --- | --- |
| GLOVE | 0.9665 | 0.9571 | 0.9622 |
| FastText | 0.9572 | 0.9583 | 0.9626 |
| Word2Vec | 0.9434 | 0.9458 | 0.9086 |
| Bert | 0.938 | 0.9388 | 0.5 |


