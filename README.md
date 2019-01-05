# Installation
Before running the code, please type 'pip install tensorflow' and 'pip install keras' in command line to install keras

In case of any problems, please type 'pip install pillow'.

# Static
This part is used to train evaluate saliency network for static images. 
main.py : the training code.
models2.py : ss_vgg describes the static network
output.py : output static salient images after training

# Dynamic
This part is intended for saliency network for spatiotemporal features underlying frames.
static.py : the training code for the static network
dynamic.py : the training code for the dynamic network
models2.py : ss_vgg describes the static network while the ds_vgg describes the dynamic network
output_dynamic : output dynamic salient images after training
output_static

# Dataset
To get weight file and the full dataset, please click the following link for downloading:

We randomly split the whole dataset and train, where 80 percent is used for training and the rest is left for evaluation

