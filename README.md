# TensorflowJS - Introduction

Hello World! Here is a simple web classifier written in the Tensforflow Javascript framework. TensorflowJS is a high level 
machine learning framework that lets users trian and deploy machine learning models right in the browser. This keeps the data 
at the client end, maintaing data security, saves begginers from setting up complex infrastructres and GPU accelerated 
frameworks.

# Workflow

The *index.html* captures an input image from 
your devices webcan. The *index.js* file then transforms it into matrix representation and passes it the **Mobilenet** 
architecture. The internal activation of mobilenet 
(since "neurons" in neural nets "activate" to the presence of features in our image) 
for this image is then passed to a K-nearest neigbour classifier. When predicting, 
the model returns the class that has the closest activation to the image we had passed it. 

# How to use this

TensflowJS is ridiculosuly simple, no virtual environments, IDE's,ananconda or pyenv distributions or expensive GPU's. 
All you need is a text editor! Submile Text, Atom what have you. Create two files **index.html** and **index.js**. Copy paste
the code you find in this repo into both of them. Open **index.html** your favortie broswer, and your good to go!

# DEMO 
Here is a link to the app https://youtu.be/KrnZthU4Jgo
