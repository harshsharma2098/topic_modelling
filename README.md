# The two .ipynb files, one in each folder can be run on local system using jupyter notebook or on Colab/Kaggle kernel.

1. BERTopic contains file and all the required installations are mentioned in it.
   Article and links referred : https://towardsdatascience.com/topic-modeling-with-bert-779f7db187e6

   https://github.com/MaartenGr/BERTopic
2. contextual_topic_identification contains file which is inspired from the below mentioned article. 
   The source code is modified and require different kind of dependencies and installation which is based on the type of kernel used.
   Article link: https://blog.insightdatascience.com/contextual-topic-identification-4291d256a032

# The above used models are trained on different datasets

1. BERTopic was trained on the popular 20 Newsgroups dataset which contains roughly 18000 newsgroups posts.
   This can be downloaded using sklearn library that contains a lot datasets.

2. Contextual topic identification model was trained on "COVID-19 Open Research Dataset Challenge (CORD-19)" dataset.
   This is a very large dataset and requires high computational power to deal with.
   link: https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge/tasks
