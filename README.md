# Development of machine learning models to detect Arrythmia based on ECG data: Class Imbalance

## Level 4 Honours Individual Project
### Ruchira Ravishankar, 2300294r

This project addresses the class imbalance problem in ECG data and explores the use of VAEs to produce synthetic ECG beats. It also uses a classifier to test the quality of the synthetic beats produced and whether they have an impact on imbalanced classification.
The following gives an overview of the Jupyter Notebooks present and what each of them do.
It is highly recommended to run the notebooks on Google Colaboratory. However, the notebooks can also run locally.

## Important
Please be aware of changing any paths in the notebooks. All cells with loading and saving files have been flagged with the comment "change path as required". Please pay special attention to this as there is a lot of data being saved and loaded by each notebook.

## Dataset
Download the dataset from https://www.physionet.org/content/mitdb/1.0.0/ and save to the appropriate path as required by the Data Preprocessing notebook.


## Notebooks to run in order

### PreProcessing, Clustering, Classification
1. Data Preprocessing - preprocesses raw mit-bih data
2. Sampling MLII Beats Only for Generative Models - creates train and test files that will be required for the VAEs
3. Clustering - clusters the unsampled test dataset with PCA, TSNE, UMAP
4. Classifier - Runs the classifier on Naive resampled data (not required to run as it is run in the cross validation notebook)

### VAE Files

Trains and tests the VAE. Visualises Latent Space. Produces synthetic data and saves in separate files for each type. For this, need to specifically train per type of beat. Can set the type of beat at the top of the file.

5. Convolutional_VAE
6. Convolutional_Sparse_VAE
7. LSTM_VAE
8. LSTM_Sparse_VAE

### Evaluation
9. Synthetic Data and Visualisation - Reads in synthetic data of each type per VAE and combines to produce one data file of synthetic data per VAE (4 data files produced in total)
10. Cross Validation for all Datasets - Runs cross validation on CNN classifier and RFC on all datasets.
11. Statistical Tests - Statistical tests on cross val results
