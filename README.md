# Deep-Learning
Eﬃcient CIFAR-100 Modelling

## Task 1 - classifier Model

Design and train a classifier model using the CIFAR-100 dataset, reporting both the training and testing accuracy. However, your model must have fewer than 100,000 (one hundred thousand) parameters. Furthermore, you may not train the neural network for more than 10,000 (ten thousand) optimisation steps. You must clearly state the total number of parameters and optimisation steps in both the code and report.


## Task 2 - classifier Model

Design and train a generative model using the CIFAR-100 dataset, train a deep generative model to synthesise unique images that will be judged on their realism, diversity and uniqueness from the original training data. 

Limitations in terms of model size and training length also apply to the generative modelling task. Your model must have fewer than 1,000,000 (one million) parameters. Note that if your approach consists of multiple networks (e.g., like a GAN), the parameter limit applies to the whole model with all the networks combined (e.g., the parameter count of the generator and the discriminator added together should be less that 1,000,000). 

Furthermore, you may not train the neural network for more than 50,000 (fifty thousand) optimisation steps. Each optimisation step is counted when your entire model is trained by calculating the gradients for the whole model once. You must clearly state the total number of parameters and optimisation steps in both the code and report.
