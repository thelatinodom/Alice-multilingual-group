# Alice-multilingual-group
Shared group repository for LIN_301 Homework #7. 
Group member names and roles:
  Bellamy Martin, Erin Aycock, Dom Luthje, Dylan High
  
Languages analyzed:
  English, French, Spanish, Finnish, Italian
  
Instructions to reproduce results:

  
Dependencies or model names (en_core_web_sm, fr_core_news_sm, etc.):
  from collections import Counter
  from unidecode import unidecode   
  from pathlib import Path
  from wordcloud import WordCloud
  import spacy
    from spacy.tokens import Token
      from spacy_wordnet.wordnet_annotator import WordnetAnnotator
      from spacy import displacy
      from spacy.matcher import PhraseMatcher
         English:	spacy.load("en_core_web_sm")
         French:	spacy/load("fr_core_news_sm")
         Spanish:	spacy.load("es_core_news_sm")
         Finish:  spacy.load("fi_core_news_sm")
         Italian: spacy.load("it_core_news_sm")
  import pandas as pd
  import matplotlib.pyplot as plt
  import pycountry
  import nltk
    from nltk.corpus import wordnet as wn
    from nltk.corpus.reader.wordnet import NOUN, VERB, ADJ, ADV
  import itertools
  import numpy as np
  import re
