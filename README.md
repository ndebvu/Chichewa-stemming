<h1>Stemming of Chichewa words</h1>
<b>Description</b>

Algorithm for stemming Chichewa words by stripping affixes of similar words in a cluster and then extracting the most common character 4-grams of the resultant words in the cluster. The clustering of the words is done using a pre-trained Fasttext word embedding model, which clusters words by considering linguistic and context information and is capable of constructing vector representations of out-of-vocabulary (OOV) words, taking them into account. We evaluated the efficacy of our algorithm in comparison to the affix parsing method. The empirical findings revealed that our approach surpasses the affix parsing approach, registering an F1 score of 62% and an accuracy of 70%. 
