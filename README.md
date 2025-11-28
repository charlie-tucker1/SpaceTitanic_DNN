# SpaceTitanic_DNN
A deep neural network created for the Space Titanic Kaggle Competition. This model achieved 79.6% accuracy, which is pretty good for a neural net on such a small dataset. 

The best models in this competition likely use some ensemble of gradient boosting and decision tree/forest models. But I want to practice PyTorch on a smaller scale, so I built this.

It uses some feature engineering; Entity embedding (as opposed to one-hot) to handle categorical data, specifically the Cabin field, Added a total spend category to help the model learn 'richness' of passengers
I also scaled and imputed data with scikit learn
