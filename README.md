# Alice-multilingual-group
Shared group repository for LIN_301 Homework #7. 
Group member names and roles:
  Bellamy Martin, Erin Aycock, Dom Luthje, Dylan High
Languages analyzed:
  English, French, Spanish, Finnish, Italian
Instructions to reproduce results:
  
Dependencies or model names (en_core_web_sm, fr_core_news_sm, etc.):
  import spacy
    python -m spacy download en_core_web_sm
    from nltk.corpus import wordnet as wn
    from nltk.corpus.reader.wordnet import NOUN, VERB, ADJ, ADV
    from spacy_wordnet.wordnet_annotator import WordnetAnnotator
    from spacy import displacy
  import pandas as pd
  from collections import Counter
  import matplotlib.pyplot as plt
  
