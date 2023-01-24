# Automatic sorting of usable and non usable waste at the Pontificia Universidad Javeriana Cali using DeepLearning 
Degree work for the degree of Electronic Engineer.

## By: 
  - *Juan Esteban Torres Tamayo*
  - *Janner Arley Rosero Mora*
 
## Thesis Director:
  - *PhD. Hernán Dario Vargas Cardona*

## Abstract:
The processing of solid waste is a problem that has been affecting humanity for several years,
resulting in pollution and excessive accumulation of waste in landfills. All this panorama has brough
the application of regulations for the classification of waste for further processing, where in Colombia
the current regulations dictate three types of waste: Usable, Non Usable and Organic. However,
even with the existence of regulations and educational campaigns on the management of urban
solid waste, the community does not adequately separate these materials and this brings with it an
increase in labor energy in the facilities dedicated to the processing of waste that seek to give them
a correct treatment.
This work proposes the implementation of a technological tool that allows the automatic classification
of organic waste focusing on the facilities of the campus of the Pontificia Universidad
Javeriana Cali. For this purpose, computer vision will be used for the recognition of waste images
which will be processed and classified from a Deep Learning algorithm that aims to identify and
classify waste between usable and non-usable.

## Models:
In this project we have used 6 models of architectures, each model has been applied with Transfer Learning methods. The models are as follows:

- InceptionV1 «Fine Tuning»
- ResNet50V2 «Fine Tuning»
- MobileNetV3 «Fine Tuning»
- MobileNetV3 + SVM «Feature extractor»
- VGG19 «Fine Tuning»
- VGG19 + SVM «Feature extractor»

## Dataset:
This dataset contains a total of 2015 photos (1015 of usable and 1000 of non-usable waste). Within this photos you can find food packaging, plastic and glass bottles, napkins, batteries, among others.

An example of photos of usable and non-usable waste is shown below:

### Usable
![Usable waste picture](51.jpg)

### Non-usable
![Non-usable waste picture](147.jpg)

Dataset available in the following link: https://drive.google.com/drive/folders/1Juy3mwwbKxS25jGUhr4gWGNkdIkjnA0d?usp=share_link
