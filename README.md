# Heartbeat-Classification

A CNN model based on classification of heartbeats into different pre-defined classes made as a group project with help from kaggle. The dataset used to train was MIT-BIH Database, downloaded from physionet.
Contains ECG signals, already filtered and annotated with either of the 5 heartbeats. Developed a 5 layerd convolution neural network model. 
Achieved an accuracy of greater than 90 % on most ecg signals. 
Modules used: SciKit, Matplotlib, numpy, panda.

A seperate model is created for the beat extraction from raw ECG signals which can then be fed into the CNN model for classification. HeartPy Module was used for R-peak detection and filtering of signals.The sample data was acquired from a European Medical site. It contains raw signals from patients admitted to a hospital.Sampled at 125 Hz
