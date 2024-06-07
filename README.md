# CoChangeFinder-Replication-Package

This replication package is created for the paper titled "Don’t Forget to Change These Functions! Early Recommending Co-Changed Functions in Modern Code Review".

## Something you need to know before start
Since the limitation of file size that allow to uploading to github, this repo only includes README. To re-generate the result in the paper, please follow "Replicate the experiment" section below. If the practioners want to train the model by themself, please download the entire replication package from [here](https://doi.org/10.5281/zenodo.11515868). The replication package includes all dataset and model used in the paper. Note that it is possible that the package is not accessible via Zenodo. In this case, please use the [backup](https://drive.google.com/file/d/1H1XDX7sqYBSEFLHZ4UGr9wd7eiar57V4/view?usp=sharing).

## Description

We implement the experiment with Python and Jupyter notebook.

## Getting Started

### Experimental environment
* We implemented our experiment on Google Colab environment. As the limitation of GPU RAM for Google Colab free tier users, to successfully replicate the experiment, you have to subscribe Google Colab Pro+ and switch GPU class to premium A100 GPU with HIGH RAM by selecting Runtime -> Change runtime type.
* We use Google drive as the file system. Please ensure the google drive have the enough storage (~2.6GB)

### Package dependencies
|                      | Packages                                                                                                            |
|----------------------|---------------------------------------------------------------------------------------------------------------------|
| Python               | dgl, iteration-utilities, sentencepiece, tojenizers, transformers, sentence-transformers, scipy, networkx           |


### Replicate the experiment
* Download dataset [here](https://doi.org/10.5281/zenodo.10584858)
* Place all folders into Google drive
* Set the url path to your location of the downloaded data in Google drive.
* Run the run.ipynb from top to bottom.
