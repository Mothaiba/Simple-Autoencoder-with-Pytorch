# Simple-Autoencoder-with-Pytorch
This short block of codes shows how to train an Autoencoder using Pytorch.

### Data
Data is provided by Riiid Labs in the [AIEd Challenge 2020 on Kaggle](https://www.kaggle.com/c/riiid-test-answer-prediction/data).

### Objective
The target of the competition is to predict if a student will give the right answer for a question, given various metadata. \
With this autoencoder, we aim to compress the tags of each question (there are in total 188 different tags) and use this compressed version (a 4-dimentional vector) as a feature to feed into our predictive models.

### Sample performance

![sample performance of the autoencoder](sample_encoding.png "Autoencoder on question tags")