# What is Regularization in ML ?

When we train a model on a data set - we often need to assess how well the model 'fit' the data. This can have three outcomes

1. Model fits the data (well)
This implies that the model has achieved its goal of fitting the data as best as it can. Any validation or new data conform to the model, and the model will be able to predict the outcome accurately.

2. Model underfits the data
Underfitting implies that the model does not perform as well as one would expect on the data. This may be due to insufficient data in the training set or a poorly chosen algorithm for the type of data.

3. Model overfits the data
Overfitting is observed when too many features, than necessary, were employeed to train a model. The validation loss increases - implying that though the model performed well on the training set, it did not perform equally well on the validation set.

# Regularization 
This is a technique or a collection of techniques to prevent or reduce overfitting. 

1. L1 (Lasso) and L2 (Ridge) regularization
 L1 -> set unneeded feature coefficients to 0
 L2 -> constrains a model's features
 
 2. Dropout 
 randomly remove parts of the model, so that rest of it has to become better
 
 3. Early Stopping
 Stop your model from training before the validation loss starts to increase too much.
 
 4. Data Augmentation
 Manipulate the dataset to make it 'harder to learn'
 
 5. Batch Normalization
 Standardize inputs  
