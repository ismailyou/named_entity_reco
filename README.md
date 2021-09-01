# Named Entity Recognition 
NER Is the task of identifying and categorizing key information (entities) in text. An entity can be any word or series of words that consistently refers to the same thing. Every detected entity is classified into a predetermined category. 

For example, 

An NER machine learning (ML) model might detect the word “Google” in a text and classify it as a “Company”.

In this notebook will be passing over from exploiting existing models and libraries NLTK, SPACY, CRFClassifier. and then will get our hand dirty and try to train a NN model to recognize all the entities 

Language :
    -   English : Almost all the models are work fine 
    -   Frensh : Most of the models facing alot of errors
    -   Arabic : Alot of errors 
    -   Darija : Null in all libraries, but we can fine tune a pre-trained model using ARABIC
    
    
[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
[![Version](https://badge.fury.io/gh/tterb%2FHyde.svg)](https://badge.fury.io/gh/tterb%2FHyde)
[![Python Versions](https://img.shields.io/pypi/pyversions/yt2mp3.svg)](https://pypi.python.org/pypi/yt2mp3/)
[![Open Source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://opensource.org/)
[![Github All Releases](https://img.shields.io/github/downloads/atom/atom/total.svg?style=flat)]()  
[![GitHub pull requests](https://img.shields.io/github/issues-pr/cdnjs/cdnjs.svg?style=flat)]()

## THE PLAN :

1.   What does NER mean ?
2.   How NER works ?
3.   Why it is important?
3.   Named Entity Recognition use cases
4.   Load Dependencies
5.   Load Corpus
    - Web Scraping using BeautifulSoup
    - load to the drive
6.   Basic Named Entity (NE) tagging using NLTK
        -   Word Based
        -   Sentence Based
7.   More powerful package
        -   Stanford NLP NER
        -   Spacy
8.  Sequence Model Approach to NER

        -   Inside–outside–beginning (tagging)
        -   English language
        -   Arabic & DARIJA
        
9.  Training a Neural Network for NER


            -   Train & test split
            -   Train The Model
            -   Model Evaluation

#### Dependencies :
            pandas         : 1.1.5
            tensorflow     : 2.6.0
            matplotlib     : 3.2.2
            sklearn        : 0.0
            fr_core_news_sm: 2.2.5
            google         : 2.0.3
            spacy          : 2.2.4
            re             : 2.2.1
            IPython        : 5.5.0
            nltk           : 3.2.5
            numpy          : 1.19.5
            requests       : 2.23.0
            
            
want just to see !! 

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/ismailyou/named_entity_reco/blob/main/Named_Enitity_Extraction.ipynb)

You can also launch it!

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ismailyou/named_entity_reco/blob/main/Named_Enitity_Extraction.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ismailyou/named_entity_reco/main?filepath=Named_Enitity_Extraction)
