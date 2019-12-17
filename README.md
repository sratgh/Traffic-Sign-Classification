# **Build a Traffic Sign Recognition Program**

## The goals / steps of this project are the following:
* Load the data set
* Explore, summarize and visualize the data set
* Design, train and test a model architecture
* Use the model to make predictions on new images
* Analyze the softmax probabilities of the new images
* Summarize the results with a written report

### Dependencies
This lab requires:

* [CarND Term1 Starter Kit](https://github.com/udacity/CarND-Term1-Starter-Kit)

The lab environment can be created with CarND Term1 Starter Kit. Click [here](https://github.com/udacity/CarND-Term1-Starter-Kit/blob/master/README.md) for the details.

### Dataset and Repository

1. Download the data set. The classroom has a link to the data set in the "Project Instructions" content. This is a pickled dataset in which we've already resized the images to 32x32. It contains a training, validation and test set.
2. Clone the project, which contains the Ipython notebook and the writeup template.
```sh
git clone https://github.com/udacity/CarND-Traffic-Sign-Classifier-Project
cd CarND-Traffic-Sign-Classifier-Project
jupyter notebook Traffic_Sign_Classifier.ipynb
```

## Installation / Setup

There are two ways of running this project:

**1) The first one is to use jupyter notebook**
* For get up and running with jupyter notebook please refer to the official documentation website:
[Install Jupyter Notebook](https://jupyter.org/install)
* Installing opencv can be a bit tricky. Here is a good installation doc for mac [Install Documenation for OpenCV](https://medium.com/@nuwanprabhath/installing-opencv-in-macos-high-sierra-for-python-3-89c79f0a246a)
* It is recommended to make use of virtual environments.
* After the installation you should be able to start the project with
`jupyter notebook P1.ipynb`

**2) The second one is to use a docker environment**
* Install Docker environment
For mac:
[Install Docker on Mac](https://docs.docker.com/v17.12/docker-for-mac/install/)
* Then pull the udacity docker environment with
`docker pull udacity/carnd-term1-starter-kit`
* Run the jupyter notebook in a docker environment with the following command:
`docker run -it --rm --entrypoint "/run.sh" -p 8888:8888 -v `pwd`:/src udacity/carnd-term1-starter-kit`

## License

This project is licensed under the MIT License.
[LICENSE](https://github.com/sratgh/Lane-finding/blob/master/LICENSE)
