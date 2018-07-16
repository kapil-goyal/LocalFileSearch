# Local File Search

A python app which enables us to search through files of a folder using techniques similar to advanced search engines and information retrieval.  
The project uses [Okapi BM25](https://en.wikipedia.org/wiki/Okapi_BM25) algorithm, [inverted index](https://en.wikipedia.org/wiki/Inverted_index) data structure, [stemming](https://en.wikipedia.org/wiki/Stemming), removing [stopwords](https://en.wikipedia.org/wiki/Stop_words) and [caching](https://en.wikipedia.org/wiki/Cache_(computing)) to make the search as fast and relevant as possible.


## Getting Started

Clone or fork the repo to make changes and test the app.


### Installing

Create a vitual enviroment if you have deal with multiple python projects.

```
sudo apt-get install python-virtualenv
or
sudo easy_install virtualenv
or
sudo pip3 install virtualenv
```

```
mkdir ~/virtualenvironment
virtualenv ~/virtualenvironment/my_new_app
cd ~/virtualenvironment/my_new_app/bin
source activate
```

To install dependencies.

```
sudo pip3 install -r requirements.txt
```


Finally run

```
python3 main.py
```


## Additional Frameworks required

* [NLTK](https://www.nltk.org/) - NLTK is a leading platform for building Python programs to work with human language data.


## Authors

* **[Vivek Raj](https://github.com/codervivek)**
* **[Rohit Pant](https://github.com/rpant1728)**
* **[Kapil Goyal](https://github.com/kapil-goyal)**
