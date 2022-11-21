# PGDM- Final Project

------

#### Objective : 

Detection of Indian food items pictures using tranfer learning with a pre-trained Model



### Approach to solving the problem:

- Import images, do eda on the dataset
- Import a pre-trained Densenet model trained on imagenet to build a new ML model to detect food items.
- Add a custom layer for model training.
- Optimizer used : adam
- Loss function : kullback_leibler_divergence
- We are creating a new custom model using tranfer learning to detect images.