# Caltech-256
Caltech-256 is a challenging set of 257 (including the last category of clutter) object categories containing a total of only 30607 images. Furthermore this dataset is imbalanced as seen in the plot below. In this exercise I utilized different Neural Network architectures and compare their performance. This project took me exactly 1 month because of the scale of the problem and the training and tweaking multiple CNN models most took overnight to train.

# Sample Images
![alt text](https://github.com/nickbiso/Keras-Caltech-256/blob/master/Sample.png)

# Category Distribution
![alt text](https://github.com/nickbiso/Keras-Caltech-256/blob/master/imbalance_plot.png)

# Results

| Model                | Accuracy(Test-set)| 
|:---------------------------------- |:---:| 
|Fully Connected                     | 14% |
|VGG                                 | 44% | 
|Inception                           | 45% | 
|Resnet                              | 48% |  
|VGG (Transfer-Learning)             | 57% |  
|Inception (Transfer-Learning)       | 63% |  
|Inception Resnet (Transfer-Learning)| 71% |  
|Xception (Transfer-Learning)        | 66% |  

# Conclusion

As seen in the table above using a Convolutional Neural Network is a big leap in accuracy from Fully Connected Neural Networks and Transfer learning of is a significantly better than training a CNN from scratch. Furthermore, Transfer Learning is the fastest to train because you are only training a fraction of the network and in addition, it requires the least data. 

