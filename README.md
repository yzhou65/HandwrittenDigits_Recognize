# CS 584: Machine Learning - Illinois Institute of Technology

# Handwritten Digits and Letters: Recognition and Classification.


***Note: First put all Code files, Data Files and Image Files at one place.*


If you stuck anywhere, please do __python helper.py -h__ or **python helper.py --help** . 

All the informations and instructions are being displayed once you run that.  


### Dependencies

1. sudo pip install termcolor
2. pip install scikit-learn
3. Download OpenCV2 . Run bash [opencv.sh](https://github.com/hparik11/HandWritten_Digit_Classification/blob/master/data/opencv.sh) on your machine to download and setup opencv2.
4. skimage

### Datasets

1. [MNIST](http://yann.lecun.com/exdb/mnist/)
2. [Letter-Recognition](https://archive.ics.uci.edu/ml/datasets/Letter+Recognition)

### Instructions:
 
1). First to Run the [K-Nearest_Neighbors](https://github.com/hparik11/HandWritten_Digit_Classification/blob/master/code/K-Nearest_Neighbors.ipynb) file:-  
	
	1. Open ipython notebook from Command Line.
	2. Run K-Nearest_Neighbors.ipynb.
	
2). Then to run [KNN with PCA](https://github.com/hparik11/HandWritten_Digit_Classification/blob/master/code/KNN_PCA.ipynb) file: 
	
	1. Open ipython notebook from Command Line.
	2. Run KNN_PCA.ipynb.
	
3). Then to run [Random Forest](https://github.com/hparik11/HandWritten_Digit_Classification/blob/master/code/randomforest.ipynb) file: 
	
	put DecisionTreeClassifier.py and functions.py files at the same location. 

	1. Open ipython notebook from Command Line.
	2. Run randomforest.ipynb.

### Results:

#### Digit Input Image

![Input Image](https://github.com/hparik11/Handwritten_Digits_Recognition_Classification/blob/master/Data%20%26%20Images/harsh.png)


#### Digit Output Image

![Output Image](https://github.com/hparik11/Handwritten_Digits_Recognition_Classification/blob/master/Data%20%26%20Images/Resulting%20Image_harsh1.png)


#### Accuracy of K-NN with PCA Algorithm by varying the Number of Features

![KNN_PCA](https://github.com/hparik11/Handwritten_Digits_Recognition_Classification/blob/master/Data%20%26%20Images/KNN_Accuracy.png)


#### Accuracy of Random Forest by varying Number of Features

![Random_Forest](https://github.com/hparik11/Handwritten_Digits_Recognition_Classification/blob/master/Data%20%26%20Images/Random_Forest_Accuracy.png)

