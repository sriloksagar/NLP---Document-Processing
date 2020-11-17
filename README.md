![alt text](https://github.com/[sriloksagar]/[NLP]/blob/[branch]/README.image.png?raw=true)


 **Morphological operations** 
  Thresholding, Removing / omitting horizontal and vertical lines in case of tables so that the text supplied to the OCR engine will be clear of noise. 

**OCR - to obtain the text** 
  Tesseract and other Deep Learning Models 

**NLP - to understand the text**
  Libraries - NLTK, SpaCy (each has language models that are used for specific type of document like scientific, medical, general English etc.).
  
**NER (Named Entity Recognition)** - Performs various text operations like tokenizing, Bag of words, Vectorization.Different models can be used like  StanfordNER, SpaCy etc. and our use case depends on the kind of document we are looking to process. Most models also have the sentence tokenizers and   hence they return sentences apart from entities. 

**Data capture using bounding boxes** - After obtaining the entities, a search bar can be implemented to locate the text in the document. This can further be used to identify the value of interest which is around that bounded text. 

**Document Classification** - There are models which perform all the mentioned above operations and identify one sentence or word that classifies the given documents. E.g.- BERT, ALBERT both by Google Research. 

**Keras OCR**
Using Keras library to define train our own OCR model and also perform Bounding Box Regression. 
Building an LSTM model for text recognition from the bounding boxes. 
 
