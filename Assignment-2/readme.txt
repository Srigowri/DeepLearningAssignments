---------------------- 1. Use CIFAR-10 dataset, [80 marks + 20 Bonus] 
a. Implement a 6-layer CNN network (Choose your own architecture) to perform classification, use the same training and testing data split as given in the dataset, Report the following 
i. Accuracy on test data by varying the Optimization Techniques 
1. Vanilla SGD [5 marks] 
2. SGD with momentum. [5 marks] 
3. Adam [5 marks] 
ii. Accuracy on test data by varying the Normalization Techniques 
1. Dropout [10 marks] 
2. Batch Normalization. [10 marks] 
iii. Accuracy on test data by varying activation function in between CNN layers, 
1. Identity. [5 marks] 
2. Sigmoid. [5 marks] 
3. ReLU. [5 marks] 
4. Tanh. [5 marks] 
iv. Accuracy on test data by varying the loss functions 
1. Cross-Entropy Loss [5 marks] 
2. MSELoss [5 marks] 
3. L1 Loss [5 marks]
Find the best configuration for your CNN (a combination of Optimization Technique, Normalization technique, activation function and Loss function), support your claim. [30 marks] 
Bonus:- Train above model for Image Embeddings with triplet loss, use these embeddings and train an SVM, report accuracy and compare it with the best model obtained in the previous exercise [20 marks] 
2. Download a ResNet 50 trained on the ImageNet classification dataset, [100 Marks] 
a. Use the features extracted from the last fully-connected layer and train binary SVM classifier for a category [from CIFAR-10 categories] of your choice. [Please update your choices in this sheet]. Report the following [20 marks] 
i. Accuracy, Confusion Matrix on test data. [15 marks] 
ii. ROC curve (assuming the chosen class as positive class and remaining classes as negative) [15 marks] 
b. Fine-tune the ResNet 50 model (you may choose what layers to fine-tune) for the CIFAR-10 dataset, and evaluate the classification performance on the test set before and after fine-tuning with respect to the following metrics [25 marks] 
i. Class wise Accuracy [10 Marks] 
ii. Choose any 5 classes and report Confusion Matrix. [15 Marks] [Code for accuracy, ROC, Confusion Matrix should be done from scratch, SVM - you may use sklearn]
