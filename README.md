# Project: Absolut3D

# Summary
  The project for the reconstruction of the human body by video. Creation of a 3d person model is performed using photogrammetry 
algorithms. To use these algorithms, the open source AliceVision library (https://github.com/alicevision/AliceVision) was taken and 
the python API was created to run this library. The UNet deep neural network model for semantic image segmentation was also 
implemented and trained. The results of the neural network are used for the model optimization algorithm.

# Tech Stack

AliceVision Library (https://github.com/alicevision/AliceVision)

Pytorch (pytorch.org)

C++ 11

Python 3.6

# Setup/Installation Guide
OS: Ubunto 16.04 

`wget https://github.com/alicevision/meshroom/releases/download/v2018.1.0/Meshroom-2018.1.0-linux.tar.gz`

`tar -xvf Meshroom-2018.1.0-linux.tar.gz`

`sudo apt-get install python=3.6`

`sudo apt-get install python3-pip`

`pip install -r requirements.txt`


# Guide to Run the API/OUTPUT
 TODO: Need to create run bash script 

run like `bash run.bash YourVideoName.mp4`
..
