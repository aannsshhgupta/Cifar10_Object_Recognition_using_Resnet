This project implements a custom Residual Neural Network (ResNet) to classify images from the CIFAR-10 dataset. 
It consists of 60,000 32×32 color images across 10 categories such as airplane, cat, and truck. 
The model is built from scratch using TensorFlow/Keras, incorporating key ResNet features like skip connections to enable deeper architectures and mitigate vanishing gradients.
The training process includes data augmentation, early stopping, and model checkpointing to enhance performance and prevent overfitting. 
After training, the model achieved an impressive test accuracy of 93.85% and a loss of 0.2317, demonstrating strong generalization on unseen data.
It also visualizes training and validation curves, and includes evaluation using a confusion matrix and sample predictions.
