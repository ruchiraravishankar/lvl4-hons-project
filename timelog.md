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
* *5 hours* patient split of data to fix train test split due to test data having synthetic data, confusion matrices created

### 19 Nov 2020
* *3 hours* Research on VAEs,  made notes on Bengio, Yoshua, Courville, Aaron, Vincent, Pascal, Representation Learning: A Review and New Perspectives

### 21 Nov 2020
* *2 hours* Research on VAEs, made notes on Kuznetsov, V. V., Moskalenko, V. A., Zolotykh, N. Yu., Electrocardiogram Generation and Feature Extraction Using a Variational Autoencoder
* *0.5 hours* created slide deck for supervisor meeting

## Week 9

### 23 Nov 2020
* *4 hours* Built Basic Autoencoder in PyTorch

### 26 Nov 2020
* *2 hours* fixed patient split to beat split and made new conf matrices

### 29 Nov 2020
* *1 hour* ran xg boost model on new split of dataset
* *0.5 hours* created slide deck for supervisor meeting


## Week 10

### 1 Dec 2020
* *2 hours* trying to centre the heart beats and remove padding

### 5 Dec 2020
* *3 hours* progress on deep autoencoder

### 6 Dec 2020
* *4 hours* progress on convolutional VAE adapting from 2d to 1d
* *0.5 hours* created slide deck for supervisor meeting

## Week 11

### 12 Dec 2020
* *2 hours* Built Linear VAE

### 14 Dec 2020
* *3 hours* working with convolutional layers for VAE

### 15 Dec 2020
* *3 hours* status report

### 16 Dec 2020
* *3 hours* research on VAEs for literature review, finding papers
* *0.5 hours* created slide deck for presentation meeting

## December Break

### 21 Dec 2020
* *4 hours* building convolutional VAE, fixing dimensionality errors

### 27 Dec 2020
* *3 hours* fixing dimensionality errors in conv VAE

### 29 Dec 2020
* *3 hours* literature review research on VAEs and VSCs

### 31 Dec 2020
* *3 hours* literature review

### 2 Jan 2021
* *2 hours* literature review

### 4 Jan 2021
* *3 hours* debugging conv VAE progress

### 7 Jan 2021
* *4 hours* trying to adapt model from gyawali et. al.

### 9 Jan 2021
* *2 hours* literature review
* *0.5 hours* created slide deck for supervisor meeting

## Week 12

### 12 Jan 2021
* *3 hours* convolutional VAE working, all errors fixed

### 14 Jan 2021
* *4 hours* working on LSTM VAE

### 16 Jan 2021
* *3 hours* research on evaluation techniques
* *0.5 hours* created slide deck for supervisor meeting

## Week 13

### 19 Jan 2021
* *3 hours* centred the beats

### 21 Jan 2021
* *3 hours* changing layers in conv vae to improve performance

### 23 Jan 2021
* *2 hours* changing layers in conv vae to improve performance
* *1 hours* planned dissertation structure

### 24 Jan 2021
* *4 hours* building LSTM VAE
* *0.5 hours* created slide deck for supervisor meeting

## Week 14

### 27 Jan 2021
* *3 hours* completed LSTM VAE model, no errors

### 30 Jan 2021
* *3 hours* Improvement on Conv VAE performance by tweaking layers

## Week 15

### 2 Feb 2021
* *5 hours* fixed LSTM VAE to produce much better results

### 4 Feb 2021
* *4 hours* trialled various losses and tweaked code for both VAEs

### 7 Feb 2021
* *0.5 hours* created slide deck for supervisor meeting

## Week 16 - Reading Week

### 9 Feb 2021
* *2 hours* normalisation of inputs to conv VAE

### 11 Feb 2021
* *1 hours* function to sample from latent space
* *2 hours* more work with denormalising output of VAE

### 14 Feb 2021
* *4 hours* background research on dissertation

### 17 Feb 2021
* *5 hours* building Conv Sparse VAE

### 19 Feb 2021
* *4 hours* continued work on conv sparse vae
* *0.5 hours* created slide deck for supervisor meeting


## Week 17

### 24 Feb 2021
* *3 hours* clustering test dataset with pca and tsne

### 26 Feb 2021
* *5 hours* clustering latent vector of conv vae, sparse vae

### 27 Feb 2021
* *4 hours* built LSTM Sparse VAE
* *1 hour* more research on evaluation techniques for VAE

### 28 Feb 2021
* *5 hours* clustering latent vector of lstm vae, lstm sparse vae
* *1 hours* generated loss plots for train and test sets
* *0.5 hours* created slide deck for supervisor meeting


## Week 18

### 2 Mar 2021
* *3 hours* trying to do latent vector visualisation
* *2 hours* Dissertation
### 4 Mar 2021
* *3 hours* completed latent vector visualisation for all models
* *1 hours* Dissertation

### 6 Mar 2021
* *2 hours* tsne clusters for all models
* *0.5 hours* created slide deck for supervisor meeting

## Week 19

### 9 Mar 2021
* *3 hours* classified synthetic data
* *2 hours* Dissertation

### 11 Mar 2021
* *3 hours* classified synthetic + real data
* *2 hours* Dissertation

### 14 Mar 2021
* *2 hours* Dissertation
* *0.5 hours* created slide deck for supervisor meeting

## Week 20

### 17 Mar 2021
* *4 hours* create all mixed datasets

### 19 Mar 2021
* *4 hours* Cross validation for all datasets and calculate performance metrics

### 20 Mar 2021
* *2 hours* Dissertation

### 21 Mar 2021
* *2 hours* Dissertation
* *0.5 hours* created slide deck for supervisor meeting

## Week 21

### 22 Mar 2021
* *2 hours* Dissertation
* *3 hours* research on statistical tests

### 23 Mar 2021
* *2 hours* Dissertation
* *3 hours* running statistical tests

### 24 Mar 2021
* *6 hours* dissertation

### 27 Mar 2021
* *4 hours* running statistical tests

### 28 Mar 2021
* *3 hours* dissertation
* *2 hours* running statistical tests
* *0.5 hours* created slide deck for supervisor meeting

## Week 22

### 30 Mar 2021 - 4 Apr 2021
* *8 hours a day* dissertation

### 5 Apr 2021
* *3 hours* presentation work

### 6 Apr 2021 - 9 Apr 2021
* *8 hours a day* final touches on presentation and dissertation
