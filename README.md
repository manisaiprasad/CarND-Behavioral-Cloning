# **Behavioral Cloning** 

---

**Behavioral Cloning Project**

The goals / steps of this project are the following:
* Use the simulator to collect data of good driving behavior
* Build, a convolution neural network in Keras that predicts steering angles from images
* Train and validate the model with a training and validation set
* Test that the model successfully drives around track one without leaving the road

# Prerequisites

To run this project, you need [Anaconda](https://www.anaconda.com) installed
To run simulator, you need  [Udacity provided simulator](https://github.com/udacity/self-driving-car-sim) 

# Installation
To create an environment for this project use the following command:

```
conda env create -f environment.yml
```

After the environment is created, it needs to be activated with the command:

```
source activate carnd-term1
```
# Running

Using the [Udacity provided simulator](https://github.com/udacity/self-driving-car-sim) and my drive.py file, the car can be driven autonomously around the track by executing 

```sh
python drive.py model.h5
```
You can train model agian by executing 
```sh
python drive.py model.h5
```
# Medium Artical (Learn More about project)
###  If you curious, check my take on this meduim artical [here](https://medium.com/@mmanisai/use-deep-learning-to-clone-cars-driving-behavior-9c8e48a849f8).




