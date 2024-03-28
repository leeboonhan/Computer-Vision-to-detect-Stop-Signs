# Computer-Vision-to-detect-Stop-Signs

## Project: Final_Project_stop_signs
## Training Run: Transfer learning for traffic sign classification

In this lab, you will train a deep neural network for image classification using transfer learning, the image dataset will automatically be download from your CV Studio account. Experiment with different hyperparameters.

In this lab you will train a state of the art image classifier using and CV Studio, CV Studio is a fast, easy and collaborative open source image annotation tool for teams and individuals. In practice, very few people train an entire Convolutional Network from scratch (with random initialization), because it is relatively rare to have a dataset of sufficient size. Instead, it is common to pretrain a ConvNet on a very large dataset in the lab, then use this Network to train your model. We will use the Convolutional Network as a feature generator, only training the output layer. In general, 100-200 images will give you a good starting point, and it only takes about half an hour. Usually, the more images you add, the better your results, but it takes longer and the rate of improvement will decrease.

- Import Libraries and Define Auxiliary Functions
- Create Dataset Object
- Load Model and Train
