# cosi-Improving-Baseline-Deep-learning-models
## first notebook(part1)
This work is divided into two notebooks, first notebook(part1) contains the baseline models and experiments to improve that model using different techniques such as data augmentation, increasing filters and layers, dropout, batch normalization and early stopping were investigated. Besides, optimization methods namely learning rate adaptive reduction is also applied to train these neural networks to avoid overfitting. 

In second part of this project(part2), I have trained a classifier on the Cifar100 dataset but rather than building and training a Convolutional Neural Network model from scratch, I have used ResNet50 model pre-trained on the ImageNet dataset as a base. Essentially, this has transfer the knowledge accumulated during the training on a large image dataset with 1000 object classes to a similar, more specific problem – classifying 100 different classes of Cifar100. This work has been divided into two sessions of training as follows

Feature extraction
Fine tunning
*Summary:*

## Second notebook(part2)
In the first notebook, I have achieved 65.42% accuracy on test set of CIFAR-100 without tranfer learning which is close to ResNet50. In the second notebook, first I have done feature extraction with ResNet50 using different deep learning techniques that I have already discussed in part 1 and achieved 75.37% accuracy by freezing the top layers of ResNet50. Later, I have trained the same model again by fine tunning all the layers but got only 1.25% improvement. Finally when I finetuned the model with learning_rate_reduction, the achieved accuracy is improved to 82.19% from 75.37%. In addition, the model has been evaluated on the images that I downloaded from google.
