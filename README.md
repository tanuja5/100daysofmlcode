# The project uses the Devangari hand written charcter dataset
# The images are stored in 46 different folders for each train and test set

These png images have 32*32 dimensions, which is flattened into a single vector.
Each image now has 1024 features related to it.

The training data is split for validation.

A simple supervised approach is taken using random forest classifier. And an accuracy of 78% is achieved.

The validation set is visualized after prediction.

Now the test set is transformed in similar way and the characters can be visualized.
