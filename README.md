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
