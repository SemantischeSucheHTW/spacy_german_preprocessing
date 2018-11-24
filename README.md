## Preprocessing

**Install:**

Install via pip:
    
    $ pip3 install spacy-german-preprocess
    $ python -m spacy download de

Or:
The project uses pipenv to manage dependencies. You can install all requirements with the following command:

    $ pipenv install
    $ pipenv shell
    $ pipenv run python -m spacy download de

    
**Still ToDo:**

 - edit stopword list
 - edit Tag list
 - maybe extend custom lemmatization json file (much work, for less output?)
 

**This Project Uses the [Spacy-IWNLP](https://github.com/Liebeck/spacy-iwnlp "Spacy-IWNLP") Lemmatizations:**



    @InProceedings{liebeck-conrad:2015:ACL-IJCNLP,
      author    = {Liebeck, Matthias  and  Conrad, Stefan},
      title     = {{IWNLP: Inverse Wiktionary for Natural Language Processing}},
      booktitle = {Proceedings of the 53rd Annual Meeting of the Association for Computational Linguistics and the 7th International Joint Conference on Natural Language Processing (Volume 2: Short Papers)},
      year      = {2015},
      publisher = {Association for Computational Linguistics},
      pages     = {414--418},
      url       = {http://www.aclweb.org/anthology/P15-2068}
    }