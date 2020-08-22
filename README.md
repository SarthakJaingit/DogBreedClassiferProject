# DogBreedClassiferProject
The _Dog Breed Classifier Project_ utilizes Convolutional Neural Networks to classify between Dog Breeds and also classify a dog breed look alike for any human.

## Dependencies 
The project is a notebook file that requires the use of several libraries. Most of them come in default when creating a new conda environment. 
`% conda create -n [conda env name] python=3`
Some of the primary packages used in the project are:

* Numpy
* torchvision
* torch 
* PIL
* cv2
* glob
* matplotlib
* os

**If any of these libraries are not in your conda environment then you can install them using the following line of code in the terminal**
`% conda install [missing package]`

For more information about Anaconda and environments please or if you need to install Anaconda then visit the [documentation](https://docs.anaconda.com/). 

## Datasets
### Import Datasets

Make sure that you've downloaded the required human and dog datasets:
Get access to the dog datasets using the repo found here in [Download Data in this repo](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-dog-classification)

Download the dog dataset. Unzip the folder and place it in this project's home directory, at the location /dog_images.

Download the human dataset. Unzip the folder and place it in the home directory, at location /lfw.

Note: If you are using a Windows machine, you are encouraged to use 7zip to extract the folder.

In the code cell below, we save the file paths for both the human (LFW) dataset and dog dataset in the numpy arrays human_files and dog_files.



