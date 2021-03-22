# Plant-Seedling-Classification
### Analysis:
We tried different  strategies to build our image classification model  using various approaches like Supervised Learning, ANN, CNN. 
Below are the disadvantages we observed:
###-Supervised Learning:
The major disadvantage with supervised learning is that it requires intensive feature engineering i.e before feeding out the flattened pixel values we need to apply tons of feature engineering over images and try to generate different features manually (which by the way gets automated to a great extent whenever we train a image classification model using CNN or even using ANN).
Also the dimensionality of the data increases which slows down the learning.

###-Artificial Neural Networks:
ANNs perform slightly better since the dense layers tend to handle lots of feature engineering without much issue. The major disadvantage with ANNs is that it cannot extract features from images the way CNN does by applying convolutions, pooling , strides etc.

###-Convolution Neural Networks:
As discussed in previous paragraph CNNs are the best when it comes to image classification. CNNs by using several combinations of Convolution layers ,strides , pooling and padding can extract or generate features which are not possible via ANNs and Supervised learning. We can also utilize pre-trained architectures like Inceptionv3, resnet50, VGG16 as part of transfer learning to improve the accuracy of our predictor models.
