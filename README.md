# Web Scraping and NLP with Requests, BeautifulSoup, and spaCy

Complete the tasks in the Python Notebook in this repository.
Make sure to add and push the pkl or text file of your scraped html (this is specified in the notebook)

## Rubric

* (Question 1) Article html stored in separate file that is committed and pushed: 1 pt
* (Question 2) Article text is correct: 1 pt
* (Question 3) Correct (or equivalent in the case of multiple tokens with same frequency) tokens printed: 1 pt
* (Question 4) Correct (or equivalent in the case of multiple lemmas with same frequency) lemmas printed: 1 pt
* (Question 5) Correct scores for first sentence printed: 2 pts (1 / function)
* (Question 6) Histogram shown with appropriate labelling: 1 pt
* (Question 7) Histogram shown with appropriate labelling: 1 pt
* (Question 8) Thoughtful answer provided: 1 pt


# Project 6: Web Scraping, NLP (Requests, BeautifulSoup, and spaCy)

## Project Objectives

This exercise is used to practice web scraping (fetching and extracting information) and processing the content from a web page. 

## Get Started

1. Copy the base repository into your Github account by selecting "use this template"
2.  Specify yourself as the owner
3. Clone the repository to your machine

## Activate Virtual Environment and Download External Environments

```bash
python3 -m venv .venv
source .venv/bin/activate
```

### Install into the virtual environment
```bash
from spacy.lang.en.stop_words import STOP_WORDS
from collections import Counter
import pickle
import requests
import spacy
from bs4 import BeautifulSoup
import matplotlib.pyplot as plt
```

### Run Cell to verify successful install 

```bash
from collections import Counter
import pickle
import requests
import spacy
from bs4 import BeautifulSoup
import matplotlib.pyplot as plt

!pip list

print('All prereqs installed.')
```


- After completion of the first question, execute the notebook and push to GitHub  using: 
```bash
git add .
git commit -m "your comment"
git push origin master   
``` 

## Export to HTML
Execute the notebook and export to HTML using
```bash
!jupyter nbconvert --to html web-scraping.ipynb
```
Commit and push your HTML files to your GitHub repo along with the executed notebooks