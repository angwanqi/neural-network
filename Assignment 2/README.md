# Neural Network Assignment
Version 1 Draft: README.md to be updated...
## Part A: Object Recognition
The project uses a sample of the CIFAR-10 dataset: https://www.cs.toronto.edu/~kriz/cifar.html
The dataset contains RGB color images of size 32x32 and their corresponding labels from 0 to 9. You will be using the batch_1 of the dataset, which contains 10,000 training samples. Testing is done on 2,000 test samples. The training data and testing data are provided in files ‘data_batch_1’ and ‘test_batch_trim’, respectively. Sample code is given in file start_2a.py.

## Part B: Text classification
The dataset used in this project contains the first paragraphs collected from Wikipage entries and the corresponding labels about their category. You will implement CNN and RNN layers at the word and character levels for the classification of texts in the paragraphs. The output layer of the networks is a softmax layer.

The training and test datasets will be read from ‘train_medium.csv’ and ‘test_medium.csv’ files. The training dataset contains 5600 entries and test dataset contains 700 entries. The label of an entry is one of the 15 categories such as people, company, schools, etc.

The input data is in text, which should be converted to character/word IDs to feed to the networks (Please refer to our given two smaple codes (CNN and RNN) which process text data in terms of character and word respectively). Restrict the maximum length of the characters/word inputs to 100 and the maximum number of training epoch to 250. Use the Adam or SGD optimizers for training with a batch size = 128 and learning rate = 0.01. Assume there are 256 different characters.
