Shakespeare Text Analysis
=========================

This project provides an opportunity apply lists, dictionaries, and tuples to explore word use in the works of Shakespeare.

Tasks
-----

You will create a program that can process an [input text file](shakespeare.txt) and output the following:

1. The total number of words in the text
2. The number of unique words in the text

When counting unique words, it is expected that you will strip any punctuation from the left or right side of a word. For this purpose, the following characters should be stripped: `,.?!'":-&;`.

In addition to stripping punctuation, words should also be counted and compared in lower case so that "The" is considered to be the same word as "the".

3. The most common word in the the text
4. The top 5 words in the text excluding stop words

You are provided with a [stopwords.txt](stopwords.txt) file. This file contains a list of commons words (a, the, an, etc) with one word per line. For one of your tasks, you will need to exclude the words found in this file from your word count.

When run, your program should produce output something like the following:



Data Sources
------------

- stopwords.txt comes from [NLTK data](https://www.nltk.org/nltk_data/)
- Shakespeare data comes from [Andrej Karpathy](https://github.com/karpathy/char-rnn/blob/master/data/tinyshakespeare/input.txt)

Resources
---------

- [PY4E Chapter 6: Strings](https://www.py4e.com/html3/06-strings)
- [PY4E Chapter 7: Files](https://www.py4e.com/html3/07-files)
- [PY4E Chapter 8: Lists](https://www.py4e.com/html3/08-lists)
- [PY4E Chapter 9: Dictionaries](https://www.py4e.com/html3/09-dictionaries)
- [PY4E Chapter 10: Tuples](https://www.py4e.com/html3/10-tuples)
