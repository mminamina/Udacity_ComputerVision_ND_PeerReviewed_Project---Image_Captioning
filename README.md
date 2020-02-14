## ComputerVision PeerReviewed Project: Image Captioning
Project 2: Image Captioning
This repository contains all of my work and comprehensive codes on Project2. 
### Project Experience
I started working on Project2 and Project3 simultaneously three weeks after program started. This project allows me to apply **Transfer Learning, LSTM, RNN, CNN, Model Inference** altogether. After testing various codes and parameters, I almost ran out of GPU. As a result, I had to significantly reduce epochs on final version. With longer training time, the model would perform much better.
### Details
- Convolutional Neural Networks (CNN) + Recurrent Neural Networks (RNN)
- **CNN**: to turn images into features
- **RNN**: to turn features into captions
### CNN-Encoder
- **ResNet** (Residual Network)
- to prevent vanishing and exploding gradients
- to employ skip connections 
- to feed the activations from one layer to another layer
### RNN Decoder
- a single LSTM layer followed by one fully-connected layer
### CNN encoder+RNN decoder
- to feed input images into CNN
- to connect CNN output to RNN input
- to find patterns
- to generate descriptive texts for images
### Worklist
For project instructions, please refer to https://github.com/udacity/CVND---Image-Captioning-Project
> The project will be broken up into four Python notebooks; 
> only Notebook 2, 3 and model.py file are graded:

### Files in Order
- data_loader.py; vocabulary.py; model.py;
- Notebook 0_Dataset.ipynb;
- Notebook 1_Preliminaries.ipynb;
- Notebook 2_Training.ipynb;
- Notebook 3_Inference.ipynb;
- Notebook 4_Zip Your Project Files and Submit.ipynb

### Additional Resources
- https://cs224d.stanford.edu/reports/msoh.pdf
- https://arxiv.org/pdf/1502.03044.pdf
- https://github.com/yunjey/pytorch-tutorial/tree/master/tutorials/03-advanced/image_captioning
- https://daniel.lasiman.com/post/image-captioning/
- https://www.groundai.com/project/cnncnn-convolutional-decoders-for-image-captioning/

#### Packages Used
Python, Pytorch, COCO Dataset, Natural Language Toolkit(ntlk)

LICENSE: This project is licensed under the terms of the MIT license.
