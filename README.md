# Deepleanring-TensorFLow
This repo is created to document my learning!
## Start up with Windows
First, we have to set up the environment.


### Install CUDA 11.2 if you want to compute code with GPU
Go [here](https://developer.nvidia.com/cuda-downloads), and download CUDA 11.2 and then choose, Windows >> x86_64 >> 10 >> exe(local). Then run the command that u see in the base installer.
#### Noteed 
Before setup CUDA you need to install Visual Studio Community 2019 (version 16.11) Go [here](https://my.visualstudio.com/Downloads?q=visual%20studio%202019&wt.mc_id=o~msft~vscom~older-downloads)
### Install CUDNN
Go to this [link](https://developer.nvidia.com/cudnn) to download CUDNN that compatible with CUDA 11.2 and then copy files in bin, include, and lib from Cudnn tv C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v11.2\bin, include,lib

### Install anaconda
Download anaconda from [here](https://www.anaconda.com/products/distribution) and the run the following command

Create deeplearning environment in anaconda
```
conda create --name deeplearning python=3.7
```
Activate the environment, install Tensorflow and other useful library
```
conda activate deeplearning
pip install tensorflow
pip install pandas numpy matplotlib opencv-python tqdm tb-nightly
pip install -U scikit-learn
```
### Install IDE
For editor, I used Pycharm.
```
pip install pycharm-community --classic
```
Run pycharm. After creating project, go to file => setting => on Project: 'name', select Python Interpreter => on setting logo, select Add... => Select conda environment => select Existing environment => (you should see deeplearning environment that we've just created)
