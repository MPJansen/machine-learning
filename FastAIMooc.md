# AWS
aws instance preinstalled
tmux terminal multiplexer
spot instances (cheap but do not sve on termination)

# Python
bcolz - fast and compact numpy array saving

# kaggle
kaggle cli

# Dynamic learning rate
1. RMS prop: divide learning rate by RMS of parameter gradient
1. Momentum: add weighted moving average of gradient to gradient direction
1. ADAM: RMSProp + Momentum
1. EVE: ADAM + learningrate annealing (difficult with stopping criterion)
1. [Cyclical Learning Rates for Training Neural Networks][3]


#Input normalization
Start with a batch norm layer (Lesson 4 58:30)

#Avoiding overfitting
1. Add more data
1. Use data augmentation
1. Use architectures that generalize well
1. Add regularization
  1. Add some norm of weights to loss function
1. Reduce architecture complexity.

#NLP
1. Word vectors, embeddings on words
1. Tokenization matters (. 's etc.)
1. Word2Vec


#Random
* Asking people about their behaviour is crap compared to looking at their behaviour

# Overview
1. [An Analysis of Deep Neural Network Models for Practical Applications][2]
1. [Systematic advances of cnns on the ImageNet][4] 
1. [Deep convolutional neural network design patterns][5]

# TODO
1. Pseudolabeling (Geoffry Hinton) Distilling knowledge
1. Spearmint hyperparameter tuning
1. Latent factors
1. checkboard pattern deconv

[Training Deep Neural Networks on Noisy Labels with Bootstrapping][1]

[1]: https://arxiv.org/abs/1412.6596
[2]: https://arxiv.org/abs/1605.07678
[3]: https://arxiv.org/abs/1506.01186
[4]: https://arxiv.org/abs/1606.02228
[5]: https://arxiv.org/abs/1611.00847
