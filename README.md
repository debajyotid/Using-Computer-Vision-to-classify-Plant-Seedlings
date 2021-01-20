# Using-Computer-Vision-to-classify-Plant-Seedlings

## Objective
Can we differentiate a weed from a crop seedling? Given an image, how do we differentiate between different plant
types?

This dataset gives us an opportunity to experiment with different image recognition techniques, as well to
provide a place to cross-pollenate ideas. The ability to do so effectively can mean better crop yields and
better stewardship of the environment.

## Dataset

The Aarhus University Signal Processing group, in collaboration with the University of Southern Denmark, has
recently released a dataset containing images of approximately 960 unique plants belonging to 12 species at
several growth stages.

Here we are provided with a training set and a test set of images of plant seedlings at various stages of growing.
Each image has a filename that is its unique id. The dataset comprises 12 plant species. The objective is to create a classifier capable of determining a plant's species from a photo. The list of species
is as follows:

● Black-grass

● Charlock

● Cleavers

● Common Chickweed

● Common wheat

● Fat Hen

● Loose Silky-bent

● Maize

● Scentless Mayweed

● Shepherds Purse

● Small-flowered Cranesbill

● Sugar beet

Link: https://www.kaggle.com/c/plant-seedlings-classification

## Acknowledgments
We extend our appreciation to the Aarhus University Department of Engineering Signal Processing Group for hosting the original data | https://vision.eng.au.dk/plant-seedlings-dataset/.

## Citation
A Public Image Database for Benchmark of Plant Seedling Classification Algorithms: | https://arxiv.org/abs/1711.05458

## Approach
We have approached to solve this problem as follows:

1. Read the images and generate the training dataset
    a. Note: We should not use the test folder as the labels are not available for the same
2. Split the data set into train and validation
3. Initialize & build the model
4. Compile and fit the model
5. Predict the accuracy for both train and validation data
