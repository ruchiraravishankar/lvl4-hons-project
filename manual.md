## User Manual

### Requirements
pip install the following libraries

* glob
* numpy
* pandas
* torch torchvision
* tensorflow
* matplotlib
* seaborn
* umap
* scikit-learn
* scikit-posthocs

Download the dataset from https://www.physionet.org/content/mitdb/1.0.0/ and save to the appropriate path as required by the Data Preprocessing notebook.

Run the notebooks in the following order.

Please change the paths accordingly. All cells with loading and saving files have been flagged with the comment "change path as required".
Please pay special attention to this as there is a lot of data being saved and loaded by each notebook.



1. Data Preprocessing - preprocesses raw mit-bih data
2. Sampling MLII Beats Only for Generative Models - creates train and test files that will be required for the VAEs
3. Clustering - clusters the unsampled test dataset with PCA, TSNE, UMAP
4. Classifier - Runs the classifier on Naive resampled data (not required to run as it is run in the cross validation notebook)


### Each VAE can either be trained on all classes or separately on each class. Change the value of the 'num' variable to control this behaviour.
5. Convolutional_VAE
6. Convolutional_Sparse_VAE
7. LSTM_VAE
8. LSTM_Sparse_VAE


9. Synthetic Data and Visualisation - Reads in synthetic data of each type per VAE and combines to produce one data file of synthetic data per VAE (4 data files produced in total)
10. Cross Validation for all Datasets - Runs cross validation on CNN classifier and RFC on all datasets.
11. Statistical Tests - Statistical tests on cross val results
