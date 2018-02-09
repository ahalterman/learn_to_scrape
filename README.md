# Learn to scrape 

Materials for MIT Methods Lab workshop on learning to scrape web pages

## Preperation

We'll be using Python 3 for this workshop. Python 3 has much better support
than 2 for different character encodings in text, which is something that comes
up quite often in web scraping.

Please install the Anaconda distribution of Python 3 and Jupyter notebook from
the [Anaconda](https://www.anaconda.com/download/?lang=en-us#macos) site. For
more details, see @soubhikbarari's instructions
[here](https://github.com/soubhikbarari/MITPolMeth-PythonDataSci-02-2018/blob/master/setup.pdf),
but making sure to install Python 3.

Once Anaconda is installed, you'll need to install a couple packages that we'll
need for web scraping. Download this repository, navigate to the directory from
the command line, and run

```
pip install -r requirements.txt
```

which will install the needed packages automatically.


## Contents

`Scraper_Skeleton.ipynb` contains a skeleton of a web scraper and is what we'll
be working through during the workshop.
