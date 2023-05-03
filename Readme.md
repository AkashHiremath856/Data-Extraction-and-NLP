# Data Extraction and NLP

# Note - `Few web pages where not found during analysis.`

# The coding was done in jupyter because is flexibility compare to scripting.

# Run `requirments.txt` first using `python3 install -r requirements.txt` then run jupyter file

### The objective of this assignment is to extract textual data articles from the given URL and perform text analysis to compute variables.

### Here pandas is used to read excel input given and export the results to `Output  Data Structure.xlsx`.

### Request module is used to get raw html from the `URL` which are availabe within `input.xlsx`.

### BeautifulSoup module of python is used for `web Scraping`.

### NLTK Punkt - This tokenizer divides a text into a list of sentences by using an unsupervised algorithm to build a model for abbreviation words.

### NLTK stopwords - Stop words are common words like ‘the’, ‘and’, ‘I’, etc. that are very frequent in text, and so don’t convey insights into the specific topic of a document. We can remove these stop words from the text in a given corpus to clean up the data.

### word_tokenize - splits a given sentence into words.

### sent_tokenize - split a document or paragraph into sentences.

### syllables - simple syllable estimator

### web scraping using requests and BeatifulSoap :

- finding title of article by h1 tag and obtain content using div tag, class name selectors.
- since different articles have different class selector used try exception to get element

# Obtaining all the variables

### By looping through multiple `URLS` we obtain variables by performing various calculations and is stored into list's. The list is inserted into dictionary with the columns as instructed.
