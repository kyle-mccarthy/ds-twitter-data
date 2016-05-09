# ds-twitter-data

## Packages

The following packages were used during development and will be required to run the Jupyter notebooks.  To install any of the following packages, SSH into the server and execute the `pip install --user [package]` command.

### Python
- [pymysql](https://github.com/PyMySQL/PyMySQL)
- [pandas](http://pandas.pydata.org/)
- [numpy](http://www.numpy.org/)
- [plotly](https://plot.ly/python/)
- [nltk](http://www.nltk.org/data.html)
- [naiveBayesClassifier](https://github.com/muatik/naive-bayes-classifier)*

**Note** for nltk the stopwords must be downloaded.  To do so open the python console and do the following:

1. `import nltk`
2. `nltk.download()`
3. `d`
4. `stopwords`

* **Note** for naiveBayesClassifier, the master branch must be used.
