# GAN-on-Simpsons
Case Study for Deep Learning at University of Toronto 

Data Source : https://www.kaggle.com/kostastokis/simpsons-faces

In this assignment you are generating sample images of Simpsons with deep convolutional generative adversarial networks (DCGANs).

You need to do the following:

1- Read and understand this tutorial: https://towardsdatascience.com/image-generator-drawing-cartoons-with-generative-adversarial-networks-45e814ca9b6b (Links to an external site.)Links to an external site.

2- Download the dataset and the source code (Jupyter Notebook) given in the tutorial. Analyze and understand the code. (Note: you need to work on images in the "cropped" folder in the dataset)

3- The code is implemented using Tensorflow. You need to change it to fully uses Keras. Please keep the structure of the code (name of the functions and so on) so it is easier to follow your code.

4- Change the code to use resized images. The original images are 128x128 but you need to resize them to 64x64 before training. You need to make required adjustments in the network to accommodate this change. Thsi will make training faster too.

5- Make sure you keep all the plotting parts of the code so you can observe how the system learns in each epoch.

6- If training on Colab will be slow, you can only run it for 50 epochs (or as many as possible). To test your code, you can run first one or two epochs. Once everything is working, then you can let it run for 50 or 300 epochs.

7- If you wanted to run it faster, you can get free trials of GPU instances on AWS or Google cloud.

8- Submit the notebook with all the results included in the notebook.
