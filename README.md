# NLP Pipeline

1. Text cleaning
    1. Convert all characters to lower cases
    2. Remove punctuations
    3. Remove symbols & carriage return
    4. Remove numbers
    5. Remove URL
2. Lemmatization
3. Tokenization
4. Padding
5. Training (A simple Long Short-Term Memory network will be used in this example)
6. Evaluation
7. Prediction

<br/>

<img src="img/pipeline.png" height=500 width=300>

<br/>
<br/>

# Pre-processing
### Why Lemmatization

Instead of simply cutting off the end or the beginning of a given word like Stemming does, Lemmatization takes care of the morphological analysis of the given word, meaning that it makes sure that the produced word is a dictionary word. 

<img src="img/lemmatization.PNG" width=400>

<br/>

### Why Padding
