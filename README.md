# DeepQRank: Generating Search Engine Rankings with Deep Reinforcement Learning

Learning to Rank is the problem involved with ranking a sequence of documents based on their relevance to a given query. Deep Q-Learning has been shown to be a useful method for training an agent in sequential decision making. 

DeepQRank, our deep q-learning to rank agent, demonstrates performance that can be considered state-of-the-art. Though less computationally efficient than a supervised learning approach such as linear regression, our agent has fewer limitations in terms of which format of data it can use for training and evaluation. 

We run our algorithm against Microsoft's LETOR listwise dataset and achieve an NDCG@1 (ranking accuracy in the range [0,1]) of 0.5075, narrowly beating out the leading supervised learning model, SVMRank (0.4958). 
