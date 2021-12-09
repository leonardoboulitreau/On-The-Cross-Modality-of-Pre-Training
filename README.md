# On The Cross-Modality of Pre-Training
This repository corresponds to the final project of the UNICAMP's master course of Deep Neural Networks for Natural Language Processing.

## Abstract
Transfer learning is a key concept in deep learning. It enables models to acquire knowledge from previously trained models, avoiding the exhaustive work to always develop them from scratch. Current state-of-the-art Natural Language Processing (NLP) models are almost entirely based on the pre-training-finetuning transfer approach. This work focuses on analysing how the models pre-trained in different domains can rapidly adapt to a different one on a downstream task. We perform a text classification experiment on the IMDB dataset with the BERT architecture loading weights from models pre-trained in speech and image, which are the Wav2Vec2.0 and the Vision Transformer (ViT), respectively. Also we experiment with finetuning directly the Wav2Vec2.0 to the text task, in order to remove any possible inductive bias for the text that could be present on BERT. Result show that the transfer only happened with from the Wav2Vec2.0, but it happened to be statistically as good as a Xavier Uniform Initialization.

## Content
All notebooks are in the experiment folder, the results are on the figures folder and the complete article is on the main branch.

## Experiments
![alt text](https://github.com/LeonardoBoulitreau/On-The-Cross-Modality-of-Pre-Training/blob/main/Results/experiments.png)

## Main Result
![alt text](https://github.com/LeonardoBoulitreau/On-The-Cross-Modality-of-Pre-Training/blob/main/Results/exp4.png)

## Authors
Diego Alysson (diegoalyssonbm@gmail.com)
Leonardo Boulitreau (leonardoboulitreau@gmail.com)
