# Eigenface Exploration: Facial Recognition in Color
December 2020
## Introduction
For our Linear Algebra Final Project, I worked with my friends Ashley Herrera, Annika Huprikar, and Alex Dyer to write a paper and prove some of the math behind the Eigenface algorithm. I then went on to implement and adapt the algorithm to recognize people's different faces in color. This README gives a high level overview of the repository containing this project. Structure:

- Code
    - ```Eigenface.ipynb```: code and documentation detailing my implementation process for the Eigenface in color algorithm.
    - ImageSet: folder containing all images used in development. Images sitting in this folder directly (not in the subfolder) will be used for training.
        - Test: folder containing image used for testing the model.
- Paper
    - ```Final_project.pdf```: pdf of our paper proving some of the math behind the algorithm, and pros and cons of our approach. 


## Run Requirements
```Code/Eigenface.ipynb``` was built using Python 3.9.0, and uses the libraries ```numpy```, ```matplotlib```, and ```os```. Please be sure to install all of these libraries in your python environment before running the notebook. 

Additionally, this notebook currently uses the exact images and their names in the ImageSet folder to operate. To use any other images in this notebook, please add them to the ImageSet folder. To change the test image, please change the path in the ```unknown_face``` variable to point to your image.



