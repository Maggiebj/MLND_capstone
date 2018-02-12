# MLND_capstone
Computer vision is an interdisciplinary field that deals with how computers can be made for gaining high-level understanding from digital images or videos. From the perspective of engineering, it seeks to automate tasks that the human visual system can do. Computer vision tasks include methods for acquiring, processing, analyzing and understanding digital images, and extraction of high-dimensional data from the real world in order to produce numerical or symbolic information, e.g., in the forms of decisions. Understanding in this context means the transformation of visual images into descriptions of the world that can interface with other thought processes and elicit appropriate action. This image understanding can be seen as the disentangling of symbolic information from image data using models constructed with the aid of geometry, physics, statistics, and learning theory.

In this project, I will try different algrithms to build a image classication model. The system is supposed to learn associations between word(lable) used to describe an image and the visual features found in it, and gets better at predicting descriptions on its own.

The candidate algrithms are:

##### CNN from Scratch
##### CNN from Transfer Learning
##### Bag of Words model combining Supervised Learning and Unsupervised Learning

In this project I use train a multi-class classifier with Caltech101 dataset to classify images from 102 classes. In addition, the model is supposed to predict an unlabeled images which upload by users and the images should be in one of the 102 classes the model is trained to identify. 
The task of the project is to develop a social image description platform on desktop, the task involved are the following:
1.	Download and processes the Caltech101 dataset
2.	Train a classifier from Caltech101 dataset by different approaches. 
3.	Evaluate the performance of the model by benchmark and find out the best approach.
4.	Design a user interface for uploading images and predict the description word.
The final application is expected to be useful for users to upload images belong to the 102 classes and the app will predict the label to describe the image.

The dataset Caltech101 is available by public: <http://www.vision.caltech.edu/Image_Datasets/Caltech101/>
