## Table of contents
* [General info]
* [Technologies]
* [Results]
* [Current status]

## General info
This project is a data analysis for generating music files through deep learning. It uses single-instrument MIDI files as data input which is simply the collection of notes and chords. The model used is an LSTM Neural Network which is able to identify long-term patterns within the data. This repository includes the input data used, the modeling and data analysis, the final output MIDI song, and the powerpoint slides of my presentation.
Initial model done by Sigurður Skúli - https://github.com/Skuldur/Classical-Piano-Composer
	
## Technologies
Project is created with:
* Python version: 3.8.5
* Music21 version: 6.7.1
* Pandas version: 1.2.3
* NumPy version: 1.19.2
* TensorFlow.Keras version: 2.4.0
* Matplotlib version: 3.3.2
	
## Results
To achieve the best results, it is recommended to train to to a minimum training validation loss of 0.05.

## Current status
Due to any potential overfitting and copyright concerns, it is recommended that this model and any results not be deployed online as a final product. 