# Alice-multilingual-group
Shared group repository for LIN_301 Homework #7. 
# Group member names and roles:
  Bellamy Martin, Erin Aycock, Dom Luthje, Dylan High
  
# Languages analyzed:
  English, French, Spanish, Finnish, Italian \
  English Text - https://www.gutenberg.org/cache/epub/11/pg11.txt \
French Text - https://www.gutenberg.org/cache/epub/55456/pg55456.txt \
Finnish text - https://www.gutenberg.org/cache/epub/46569/pg46569.txt \
Italian Text - https://www.gutenberg.org/cache/epub/28371/pg28371.txt \
Spanish Text - https://github.com/andergd/separadorSilabas/blob/master/Carroll%2C%20Lewis%20-%20Alicia%20En%20El%20Pa%C3%ADs%20De%20Las%20Maravillas.txt
  
# Instructions to reproduce results:
To reproduce the results we found, make sure to curl the same editions of texts we used from Gutenburg Press, also make sure to label them the same way used in the code. The main code is stored only in the qmd titled HW7_alsice.qmd, that qmd should include all of our code which could be copied over to new python cells and run the same way as ours does.
  
# Dependencies or model names (en_core_web_sm, fr_core_news_sm, etc.):
  from collections import Counter \
  from unidecode import unidecode  \
  from pathlib import Path \
  from wordcloud import WordCloud \
  import spacy \
  from spacy.tokens import Token \
  from spacy_wordnet.wordnet_annotator import WordnetAnnotator \
  from spacy import displacy \
  from spacy.matcher import PhraseMatcher \
  English:	spacy.load("en_core_web_sm") \
  French:	spacy/load("fr_core_news_sm") \
  Spanish:	spacy.load("es_core_news_sm") \
  Finish:  spacy.load("fi_core_news_sm") \
  Italian: spacy.load("it_core_news_sm") \
  import pandas as pd \
  import matplotlib.pyplot as plt \
  import pycountry \
  import nltk \
  from nltk.corpus import wordnet as wn \
  from nltk.corpus.reader.wordnet import NOUN, VERB, ADJ, ADV \
  import itertools \
  import numpy as np \
  import re
