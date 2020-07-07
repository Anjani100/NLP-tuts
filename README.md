# NLP-tuts
Tutorial code for NLP

## Setup

The following packages are required to be installed:

* nltk: pip install nltk

Now, after the installation, you need to add all the nltk packages. You can do that by using the following lines of codes on Jupyter Notebook (or any other python IDE):

```
import nltk
nltk.download()
```

Running this piece of code will pop up a program where you will need to select the **all** categories and then click download to download all the necessary packages and libraries.

## Tutorials

### Terminologies

* **Tokenizing:** Separates a piece of text and adds up into a list. There are generally 2 types of tokenizing namely *word_tokenizers* (separates the text word-wise) and *sentence_tokenizers* (separates the text sentence-wise).
* **lexicon:** words along with their meanings.
* **corporas:** body of text. It could be medical journals, presidential speeches, etc.

* ##### Difference between investor-speak and regular english-speak

  * **Investor-speak:** 'bull' - someone who is positive about the market.
  * **English-speak:** 'bull' - a scary animal you don't want running at you.

* **Stop Words:** Helper words such as articles (a, an, the), prepositions (on, after, before).
* **Stemming:**  Stem is used to shorten the lookup, and normalize sentences. For example, closes, closing, closed all derive from the same word *close*. Stem is used to replace all the above mentioned word with the parent word, i.e., close.
* **Part of Speech Tagging:** Labels words in a sentence as nouns, adjectives, verbs, etc. Moreover, it also labels by tense, and more.
* **Chunking:** It group words into hopefully meaningful chunks. One of the main goals of chunking is to group into what are known as "noun phrases." These are phrases of one or more words that contain a noun, maybe some descriptive words, maybe a verb, and maybe something like an adverb. The idea is to group nouns with the words that are in relation to them.
* **Chinking:** Chinking is a lot like chunking, it is basically a way for you to remove a chunk from a chunk. The chunk that you remove from your chunk is your chink.
* **Named Entity Recognition:** The idea is to have the machine immediately be able to pull out **entities** like people, places, things, locations, monetary figures, and more. Keep *binary = True* to categorize everything as NE, i.e., Named Entity.
* **Lemmatizing:** It is a similar operation to Stemming, the only difference being that stemming can often create non-existing words whereas lemmas are actual words.
* **Wordnet:** Wordnet is a lexical database for the English language, which was created by Princeton, and is part of the NLTK corpus. You can use WordNet alongside the NLTK module to find the meanings of words, synonyms, antonyms, and more.
* **Wu and Palmer Method:** It is an algorithm to determine how similar 2 words are to each other.

## Projects

### Sentiment Analysis from movie reviews

The NLTK corpus *movie_reviews* data set has the reviews, and they are labeled already as positive or negative (1000 reviews each).
For the first Machine Learning algorithm, we're going to go with **Naive-Bayes algorithm**.
* **Naive-Bayes:** This is a pretty popular algorithm used in text classification, so it is only fitting that we try it out first. 
