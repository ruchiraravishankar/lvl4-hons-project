# Timelog

* Development of machine learning models to detect Arrythmia based on ECG data
* RUCHIRA RAVISHANKAR
* 2300294R
* DR FANI DELIGIANNI

## Guidance

* This file contains the time log for your project. It will be submitted along with your final dissertation.
* **YOU MUST KEEP THIS UP TO DATE AND UNDER VERSION CONTROL.**
* This timelog should be filled out honestly, regularly (daily) and accurately. It is for *your* benefit.
* Follow the structure provided, grouping time by weeks.  Quantise time to the half hour.

## Week 1

### 30 Sept 2020

* *1 hour* Read the project guidance notes
* *0.5 hour* Created GitHub repository

### 1 Oct 2020

* *2 hours* Read the reference papers supervisor sent to gain initial understanding

### 2 Oct 2020
* *2 hours* Read the research papers supervisor sent to gain initial understanding

## Week 2

### 5 Oct 2020

* *0.5 hours* meeting with supervisor

### 8 Oct 2020
* *0.5 hours* Learnt how to read an ECG signal
* *2.5 hours* Read the data into Jupyter notebook
* *0.5 hours* Created Powerpoint slides to track progress
* *1.5 hours* Started work on visualising ECG data

### 11 Oct 2020
* *3 hours* Continued work on visualising ECG data and analysis of the data

## Week 3

### 12 Oct 2020
* *0.5 hours* meeting with supervisor
* *2 hours* mapped annotations onto graph of ECG

### 13 Oct 2020
* *3 hours* worked on segmenting data into the annotated classes

### 14 Oct 2020
* *3 hours* worked on extracting each heartbeat from data

### 15 Oct 2020
* *1.5 hours* research on creating dataset from extracted beats
* *0.5 hours* research on standardisation vs normalisation

### 16 Oct 2020
* *3 hours* standardised all beats, removed unclassified beats

### 17 Oct 2020
* *2 hours* fixed bugs in function to segment heart beats from dataset
* *1 hour* worked on saving all signals in csv files

### 18 Oct 2020
* *2 hours* fixed some more bugs in the code
* *1 hour* created slide deck for supervisor meeting with updates

## Week 4

### 19 Oct 2020
* *0.5 hours* meeting with supervisor

### 20 Oct 2020
* *1 hour* PhD student presentation
* *2 hours* Research on upsampling and downsampling data

### 22 Oct 2020
* *2 hours* wrote code to upsample and downsample dataset

### 23 Oct 2020
* *3 hours* revisited upsample downsample functions to replace with sklearn functions
* *1 hour* implemented LOOCV to segment data into training and testing sets

### 24 Oct 2020
* *2 hours* Research on Data Visualisation
* *4 hours* Learnt and tested running code on the GPU cluster and creating own docker image

### 25 Oct 2020
* *6 hours* Created UMAPs for raw data to identify clusters for all beats - inter-patient
* *0.5 hours* created slide deck for supervisor meeting

## Week 5

### 26 Oct 2020
* *0.5 hours* supervisor meeting
* *1 hour* Added patient number to data in order to be able to group by patient

### 27 Oct 2020
* *2 hours* Research on visualising high dimensional data, t-SNE vs UMAP

### 29 Oct 2020
* *3 hours* Created 75/25 split of data and trained it on xgboost model
* *2 hours* trained data on various support vector machines

### 31 Oct 2020
* *2 hours* Visualised model predictions with UMAPs
* *2 hours* Implemented Leave One Patient Out, fixing LOOCV from last week

### 1 Nov 2020
* *2 hours* Research on other ways of visualising high-d data
* *0.5 hours* created slide deck for supervisor meeting

## Week 6

### 2 Nov 2020
* *0.5 hours* meeting with supervisor

### 3 Nov 2020
* *2 hours* Research on CNNs and how they work, 1D CNNs in particular

### 5 Nov 2020
* *2 hours* Created confusion matrices for ML models so far

### 7 Nov 2020
* *2 hours* Read PyTorch Recipes book to learn about building CNNs in PyTorch
* *0.5 hours* Calculated various metrics to measure performance of models (F1, precision, recall)
* *5 hours* Building a first attempt 1D CNN in PyTorch
### 8 Nov 2020
* *0.5 hours* created slide deck for supervisor meeting


## Week 7

### 9 Nov 2020
* *0.5 hours* meeting with supervisor
* *0.5 hours* fixed confusion matrices to reflect performance per class

### 10 Nov 2020
* *5 hours* Worked on PyTorch CNN

### 11 Nov 2020
* *2 hours* Ran models on imbalanced dataset and created confusion matrices for comparison

### 12 Nov 2020
* *4 hours* Built a complete 1D CNN in Keras and ran it

### 13 Nov 2020
* *2 hours* Research on variational autoencoders

### 14 Nov 2020
* *0.5 hours* created slide deck for supervisor meeting

## Week 8

### 18 Nov 2020
* *3 hours* patient split of data to fix train test split due to test data having synthetic data, confusion matrices created

### 19 Nov 2020
* *3 hours* Research on VAEs,  made notes on Bengio, Yoshua, Courville, Aaron, Vincent, Pascal, Representation Learning: A Review and New Perspectives

### 21 Nov 2020
* *2 hours* Research on VAEs, made notes on Kuznetsov, V. V., Moskalenko, V. A., Zolotykh, N. Yu., Electrocardiogram Generation and Feature Extraction Using a Variational Autoencoder
* *0.5 hours* created slide deck for supervisor meeting
