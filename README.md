# OCR

This project aims to spell check physical documents on the go. The spell checking Python script uses simple probability concepts to check if spellings are correct, or incorrect. If an erratum is detected, it checks if it requires 1 or 2 changes (insertion, deletion, swap, replacement, etc.) and suggest word(s) that require the least number of changes. The Optical Character Recognition utilises the k - Nearest Neighbour Algorithm and OpenCV to scan text from documents

# Part 1: SpellCheck

Code samples and additional resources on how to make a decent and pretty fast spell check

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software 

```
python 2.7.x 
```

### Read up about 
- Regular Expressions RegEx http://www.pitt.edu/~naraehan/python2/re.html 
- Counter objects from collections https://docs.python.org/2/library/collections.html


### Installing

Clone or download the repository. 

Open spellcheckernorvig.py in your favorite editor. 

Everything is pretty much there. Go ahead and run it! 


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


## Acknowledgments

Hats off to [Peter Norvig](https://github.com/norvig)'s amazing tutorial [here](http://norvig.com/spell-correct.html) for taking the time out to blog. 
> Also, don't forget to check out his personal blog. You'll end up finding hidden gems there 😉


## Additional Resources

Most of this has been taken from (_again_) Peter Norvig's spell - checker tutorial. I'm mentioning some of them here: 

- http://nbviewer.jupyter.org/url/norvig.com/ipython/How%20to%20Do%20Things%20with%20Words.ipynb 
>   Statistical Natural Language Processiong in Python 


- http://ota.ox.ac.uk/headers/0643.xml
>   Birkbeck Spelling Error Corpus: Computer Readable English Spelling errors 


- http://norvig.com/ngrams/ 
>   The code and data by Peter Norvig to Natural Language Data: Beautiful Data 


- http://www.dcs.bbk.ac.uk/~roger/spellchecking.html 
> Spell - checking by computers, survey article by Roger Mitton 


- http://alias-i.com/lingpipe/demos/tutorial/querySpellChecker/read-me.html 
> Spelling - checker tutorial by the LingPipe project 


- http://aspell.net/ 
> The aspell project and oh! They have better test data [here](http://aspell.net/test) 


_In case you forgot, our test data is big.txt_ 

# Part 2: K Nearest Neighbour using Optical Character Recognition [stay tuned!]
