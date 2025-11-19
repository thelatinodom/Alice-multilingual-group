# Alice-multilingual-group
Shared group repository for LIN_301 Homework #7. 
Group member names and roles:
  Bellamy Martin, Erin Aycock, Dom Luthje, Dylan High
  
Languages analyzed:
  English, French, Spanish, Finnish, Italian
  
Instructions to reproduce results:

  
Dependencies or model names (en_core_web_sm, fr_core_news_sm, etc.):
  import spacy
   English:	en_core_web_sm
   French:	fr_core_news_sm
   Spanish:	es_core_news_sm
   Finish: fi_core_news_sm
   Italian: it_core_news_sm
    from spacy.tokens import Token
    from nltk.corpus import wordnet as wn
    from nltk.corpus.reader.wordnet import NOUN, VERB, ADJ, ADV
    from spacy_wordnet.wordnet_annotator import WordnetAnnotator
    from spacy import displacy
    from spacy.matcher import PhraseMatcher
  import pandas as pd
  from collections import Counter
  import matplotlib.pyplot as plt
  from unidecode import unidecode
  import pycountry
  from wordcloud import WordCloud
