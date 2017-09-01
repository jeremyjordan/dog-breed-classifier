[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"
[image2]: ./images/sample_human_output.png "Sample Human Output"
[image3]: ./images/vgg16_model.png "VGG-16 Model Keras Layers"
[image4]: ./images/vgg16_model_draw.png "VGG16 Model Figure"


## Overview

This is a more reader-friendly version of a project I worked on as part of my Udacity Machine Learning Nanodegree. The original project is avaiable [here](https://github.com/jeremyjordan/machine-learning/tree/master/projects/dog-project).

In this project, I'll walk through how to build a Convolutional Neural Networks (CNN) for image classification. The CNN will be able to detect whether a given photo contains a person or a dog, and if the photo contains a dog it will attempt to predict the dog's breed. If the photo contains a person, it will determine which dog breed most resembles the person.

Here's a sample of an output for a dog.
![Sample Output][image1]

And a human.
![Sample Output][image2]

## Instructions

The training data for this project is located [here](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip). This dataset contains 133 different breeds of dogs and is already split into train, test, and validation sets. Place the training, testing, and validation datasets in the `dogImages` folder. 

If you want to run this code on your local computer, you'll also need to download the bottleneck features found [here](). I'll discuss what this is in the Jupyter Notebook, but it's a relatively large file so you may want to go ahead and start the download.

I recommend setting up an environment for this project to ensure you have the proper versions of the required libraries.

Note: You must navigate to the root folder of the project directory in order for the following commands to work properly.


For __Mac/OSX__:
```
	conda env create -f requirements/aind-dog-mac.yml
	source activate aind-dog
	KERAS_BACKEND=tensorflow python -c "from keras import backend"
```

For __Linux__:
```
	conda env create -f requirements/aind-dog-linux.yml
	source activate aind-dog
	KERAS_BACKEND=tensorflow python -c "from keras import backend"
```

For __Windows__:
```
	conda env create -f requirements/aind-dog-windows.yml
	activate aind-dog
	set KERAS_BACKEND=tensorflow
	python -c "from keras import backend"
```

Lastly, fire up the Jupyer Notebook and let's get started.

```
	jupyter notebook dog_app.ipynb
```
