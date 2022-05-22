# News Article Recommendation Using Topic Modeling and Sentence Transformer

The notebooks compare news article recommendation using LDA topic modeling and Sentence Transoformer.<br>
Link to dataset - [BBC News Classification](https://www.kaggle.com/competitions/learn-ai-bbc/data)<br>

### Topic Modeling - LDA
Nearest Neighbor search with euclidean distance is performed on the topic distributions output from LDA to get closest documents.<br>

### Sentence Transformer
Nearest Neighbor search with cosine distance is performed on the vecotor database produced using sentence transformer which outputs a 384 vector for each document to get closest documents.<br>

As expected Sentence Transformer give better and more meaningful recommendations since Transformers are state of the art in NLP but LDA recommendations are good too.

## Sample Recommendations 

![topic-model](https://user-images.githubusercontent.com/37840005/169703841-5c9e33e2-cba9-4591-8932-664fdc440f25.PNG)
&nbsp;&nbsp;Sklearn Latent Dirichlet Allocation
<br>
<br>
![sentence-transformer](https://user-images.githubusercontent.com/37840005/169703847-c6b94991-b5dc-413d-83d4-9fdf8381c794.PNG)
&nbsp;&nbsp;Sentence Trasformer - 'paraphrase-MiniLM-L6-v2'

## Libraries
* PyTorch
* sentence-transformer
* sklearn 
* pyLDAvis
* pandas
* numpy
* tmtoolkit
* seaborn
* sumy
* gensim
* SpaCy
