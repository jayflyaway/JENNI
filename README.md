# Joint Enhancement using Neural Network Imagination

data set used as input for the DCGAN: 
https://www.kaggle.com/greg115/abstract-art

JENNI (Joint Enhancement using Neural Network Imagination) is basically a process using the selected output of a DCGAN 
trained on abstract art to generate real world painting. 

![](PaintProduction/generator/in_out.svg)

The process can be split up into three basic neural network based components:
- generating images via a DCGAN architecture
- selecting images using a discriminator
- translate the digital images to real-word paintings using a neural network based generator which is connected to motor output

