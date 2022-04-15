**UDACITY CAPSTONE PROJECT**

**PROJECT OVERVIEW**
The intent of this project is to leverage the power of Convolutional Neural Networks to train a model that could identify if a given input image is "Dog" or "Human" and the dog's breed (or the closest breed it resembles with in case of human face as the input).

### Instructions

1. Clone the repository and navigate to the downloaded folder.
```	
git clone https://github.com/prvnk10/udacity_nanodegree_capstone
cd udacity_nanodegree_capstone
```

2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/udacity_nanodegree_capstone/dogImages`. 

3. Download the [human dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip).  Unzip the folder and place it in the repo, at location `path/to/udacity_nanodegree_capstone/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder. 

4. Donwload the [VGG-16 bottleneck features](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogVGG16Data.npz) for the dog dataset.  Place it in the repo, at location `path/to/udacity_nanodegree_capstone/bottleneck_features`.

5. Switch [Keras backend](https://keras.io/backend/) to TensorFlow.
	- __Linux__ or __Mac__: 
		```
		KERAS_BACKEND=tensorflow python -c "from keras import backend"
		```
	- __Windows__: 
		```
		set KERAS_BACKEND=tensorflow
		python -c "from keras import backend"
		```
    
6. Open the notebook.
```
jupyter notebook dog_app.ipynb
```

### Libraries used
- keras
- numpy
- glob
- sklearn
- cv2
- matplotlib
- tqdm
- PIL


Blog post link:
https://prvnk10.medium.com/udacity-nanodegree-capstone-dog-breed-classification-a83d6fd43286
