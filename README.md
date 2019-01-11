# Text-Classification-Reuters21578
This exercise involves text classification of documents contained in the 6 most common categories in ModApte split of Reuters-21578 dataset learning by examples. 
So,the categories considered are :
* acq
* crude
* earn
* grain
* money-fx
* trade

The implemented and analyzed alghoritms are  :
* Perceptron


## Requirements

On first start the program needs a working Internet connection to download dataset and others files; the following times it won't be needed.

The exercise needs the following installed modules:
* SciPy
* NumPy
* NLTK    https://www.nltk.org/
* MatPlotLib
* time 

## Instructions
To run the program launch perceptron.py and then main.py. Setting of the max number of iterations to perform for each class.

## Credits

Dataset loading, vocabulary extraction and stemming process are heavily inspired by Miguel Alvarez https://miguelmalvarez.com/2016/11/07/classifying-reuters-21578-collection-with-python/ and https://miguelmalvarez.com/2015/03/20/classifying-reuters-21578-collection-with-python-representing-the-data/.

## Third libraries and modules

* NLTK library : for loading the ModApte split of Reuters-21578 dataset, deleting stopwords, Porter's stemming process
* NumPy : vector operations 
* SciPy : use matrix sparse
