# Geo2Vec


## Understanding location

## Goal
The goal of this project is to uncover the latent meaning of location, by creating Geospatial vectors that take into consideration a wide array of different data points(demographic, geographic, psychographic, environmental, temporal), so the resulting embeddings can then be used in a wide array of application. 

It will also be possible for you to access the feature(s) that matter(s) to your specific use case(income, population density, etc)

## Background
### It is all about proximity
In industry after industry people have come to understand the importance of proximity

- #### Geography: 
>> Tobler's first law of geography. "everything is related to everything else, but near things are more related than distant things."

- #### NLP: 
>> You shall know a word by the company it keeps (John Rupert Firth), which is the underline principle behind word embedding (word2vec, GloVe, etc.)

- #### Social: 
>> You Shall Know People by the Company They Keep: Person Name Disambiguation for Social Network Construction

- #### Time series: 
>> The exponential moving average are weighted moving averages that give more weighting, or importance, to recent price data than a random sample. In this case, the distance is time.

- #### Computer vision: 
>> One of the best ways to find image similarity is by using a siamese network with a triplet loss function (facenet, loc2vec, object tracking, etc), this is done by training the model on an image(anchor) and a similar/augmented image(positive) and dissimilar image (negative) and the loss function attempts to maximize the distance between the anchor and negative image.

- #### Structured Data: 
>> A wide range of companies create and use embedding to understand the latent features of their subject of interest (pins, House, stores, products, industry2vec, etc) by using similarity/proximity measurement

## Methodology 
