# Detecting-Mental-Health-Conditions-on-Reddit-using-NLP-and-machine-learning-
This repository contains classification models that I have created for my Master's degree project. 
Each file represetns a different model (either different classifier or same classifier but changed hyperparamenters). 

The dataset used was obtained from https://zenodo.org/record/3941387#.YUx8ay1Q1bX and modififed according to the needs of the project.
The dataset used for this project contains 12 labels, 6 mental-health and 6 non-mental health. 
Mental health subreddits are anxiety, bipolar disorder, depression, PTSD, schizophrenia, and suicidewatch.
Non-mental health subreddits are conspiracy, fitness, meditation, parenting, personal finance, and teaching.
 

For SVM models I experimented with the N-grams ( unigrams, bigrams, trigrams)+ hyperparameters( loss functions and C regulization parameter). 
For NN models I experimented with the embeddings. I trained embedding layer as a part of the model, used pre-trained Glove embeddings ( both static and fine-tuned).


Additional info: 
WD- without depression class dataset. 

5k- 5000 most frequent words

10k- 10000 most frequent words

100D- dimention of the embedding vectors 

300D-dimention of the embedding vectors 

NN- embedding layer trained as a part of the model

Glove-pre-trained Glove embeddings without fine-tuning 

Tune-pre-trained Glove embeddings with fine-tuning 
