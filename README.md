The project is implemented as a iPython notebook : svhn_classification.ipynb

List of software used in the project along with the versions that I used:
python 3.5.2
tensorflow 0.9
sklearn 0.18.1
numpy 1.11.2
pandas 0.19.1
h5py 2.6.0
matplotlib 1.5.3

Dataset used:
- The dataset is publicly available from the following web site: http://ufldl.stanford.edu/housenumbers/
- In particular, I used the format 1 of the dataset for the training and testing data
	- http://ufldl.stanford.edu/housenumbers/train.tar.gz
	- http://ufldl.stanford.edu/housenumbers/test.tar.gz

Notes on executing the script in the notebook:
A small manual step needs to be done at the beginning, namely to extract the training and testing tar.gz files that are mentioned above into their respective folders and then in the iPython notebook, just set the variable names train_folder and test_folder to the folder path where the data has been extracted.

The notebook contains further instructions and comments at each cell so just execute the cells one by one.
