***How it works***

Using Regex and nltk, input strings are cleaned for use in NLP applications using many different NLP cleaning methods, including making the string lowercase, expanding contractions, standardizing tenses of words, and tokenization (splitting a string into a list of different words in the string). These methods are carried out automatically through the function.

***Environment setup***

**Must use:**

Python 3.7 and up (I used python 3.9.6)

**Download the following packages (if not already downloaded):**

Contractions (only download version 0.0.18)

Emoji

Nltk

Regular expressions (re)

Note: For the nltk package, run the file “installnltk” in the preferred environment. A menu should come up prompting you what data to download. Download all the data available

***How to use the file***

When you need to clean any text, with emojis or without, import the “normalize\_text” function and input a string that you want to clean. The output will contain a list containing the tokenized and cleaned string in the form of a list, along with one integer which will tell you whether there were any emojis in the text. 0 for no emoji and 1 for emoji present. 


