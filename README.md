# TinyImagenet-Image-Classification

Successfully completed the Kaggle competetion "Image-Classification-Project" organised by IIT Kanpur in the 90 days "Applied Machine Learning and Data Science" training certificate program.

About the data - Image Detect challenge has 200 classes. Each class has 450 training images, 50 validation images, and 50 test images. There are training, validation and test sets with images and annotations. 

In the beginning, I implemented the network using only 3 Conv2D layers and 2 pooling and Batch Normalization Layers. But then the accuracy was very low and around 8% and the model was not learning. And then I tried to implement our network with the pretrained VGG16 model as our network. We achieved an accuracy of 70% on the training set and 33.5% on the validation set with a batch size of 32 images running for 100 epochs.
I tried various pretrained model like InceptionV3, MobileNet, DenseNet, etc. Lastly I tried with Xception model with SGD optimizer and learning rate as 0.001, I achieved an accuracy of 79% on training set and 58% on the validation set with a batch size of 32 images running for 100 epochs.
