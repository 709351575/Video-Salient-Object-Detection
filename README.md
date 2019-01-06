# Installation
Before running the code, please type 'pip install tensorflow' and 'pip install keras' in command line to install keras

In case of any problems when loading images, please type 'pip install pillow'.

# Static
This part is used to train evaluate saliency network for static images. 

main.py : the training code.

models2.py : ss_vgg describes the static network

output.py : output static salient images after training

Please run main.py first to train the network and output.py later to check results.

# Dynamic
This part is intended for saliency network for spatiotemporal features underlying frames.

static.py : the training code for the static network

dynamic.py : the training code for the dynamic network

models2.py : ss_vgg describes the static network while the ds_vgg describes the dynamic network

output_dynamic.py : output dynamic salient images after training

output_static.py : output static salient images after training

Please run dynamic.py first to train the network and output_dynamic.py later to check results.

# Dataset
To get weight file and the full dataset, please click the following link for downloading:

Static link : https://pan.baidu.com/s/1xrg5ey1IGoO-r6C1TkuqgQ
Dynamic link : https://pan.baidu.com/s/1HnsEpXR9thQrg4EabR2tjQ

We randomly split the whole dataset and train, where 80 percent is used for training and the rest is left for evaluation.

Our results (MAE) are sightly improved over the original scores reported in our paper:

Static : 0.035 Dynamic : 0.037
