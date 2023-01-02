# BERT-IMDB #
Training a sentiment model using BERT and serving the end point using Flaskl/Django

Data can be downloaded from [Kaggle IMDB Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews?resource=download).

* Make sure to add the dataset in `BERT-IMDB/input` folder and change the data file name to imdb.csv 

#This is for setting up BERT_IMDB project to train the model#


# Virtual Environment Setup
-   Create virtual environment (using python3.9)

        python3 -m virtualenv bert-imdb


-   Activate the virtual environment

        source bert-imdb/bin/activate
 

-   Install dependencies: 
    
        pip install -r requirements.txt 
