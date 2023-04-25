# Music Genre Classification Project

This repository is based on the recognition of musical genres through supervised and unsupervised learning.

## Plugins:
- numpy: https://numpy.org
- librosa: https://librosa.org/doc/latest/index.html
- matplotlib: https://matplotlib.org
- pydub: https://pypi.org/project/pydub/
- pandas: https://pandas.pydata.org
- scikit-learn: https://scikit-learn.org/stable/

## Information:
the dataset used for built this project is the notorious GTZAN dataset, recovered from kaggle (_**link to database:** https://www.kaggle.com/datasets/andradaolteanu/gtzan-dataset-music-genre-classification_). 

In the **utils** directory there are all that classes used for preprocessing the dataset and performing data augmentation (I did not use the csv file available at the previous link, I built my own).

- **_features_computation.py:_** computation of the various audio features to extract from files.
- _**features_extractions:**_ extraction of the computed features to a csv file in a proper directory.
- _**features_visualizations:**_ visualization of the single audio signals and the visualization various coputed features, confronting the different genres.
- _**prepare_datasets:**_ check the duration of audio files and performe data augmentation.

Then we have the core classes of the project:

- _**main:**_ main class of the project that calls all the other. 
- _**genres_ul_functions:**_ class that performs k-means clustering and the performs its evaluation. 
- **_genres_sl_functions:_** perform that performs various classification algorithms (Neural Network, Random Forest, K-Nearest Neighbors, Support Vector Machine) and evaluate them with confusion matrix, roc curve and metrics (accuracy, F1-score,...).
- **_plot_functions:_** class used for defining all the plot functions.
- **_costants:_** class that contain all the constats used in the project.

## Documentation
...*work in progress*...















