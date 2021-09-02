# Named Entity Recognition 
[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
[![Version](https://badge.fury.io/gh/tterb%2FHyde.svg)](https://badge.fury.io/gh/tterb%2FHyde)
[![Python Versions](https://img.shields.io/pypi/pyversions/yt2mp3.svg)](https://pypi.python.org/pypi/yt2mp3/)
[![Open Source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://opensource.org/)
[![Github All Releases](https://img.shields.io/github/downloads/atom/atom/total.svg?style=flat)]()
[![GitHub pull requests](https://img.shields.io/github/issues-pr/cdnjs/cdnjs.svg?style=flat)]()


## What is NER ?
_NER_ Is the task of identifying and categorizing key information (entities) in text. An entity can be any word or series of words that consistently refers to the same thing. Every detected entity is classified into a predetermined category. 

##### Example, 

An NER machine learning (ML) model might detect the word “Google” in a text and classify it as a “Company”.

In this notebook will be passing over the most common libraries in NLP, from exploiting existing models and libraries (`NLTK, SPACY, CRFClassifier, HuggingFace Transformers`..), then will try to train a NN model using `keras and tensorflow` to recognize all the entities 

##  Language :

<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: canter;">
      <th>Language</th>
      <th>Models Accuracy</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>ENGLISH</td>
      <td>* * * * *</td>
    </tr>
    <tr>
      <td>FRENCH</td>
      <td>* * *</td>
    </tr>
    <tr>
      <td>ARABIC</td>
      <td>* * *</td>
    </tr>
    <tr>
      <td>DARIJA</td>
      <td>* * </td>
    </tr>
  </tbody>
</table>
</div>

## THE PLAN :

1.   What does NER mean ?
2.   How NER works ?
3.   Why it is important?
3.   Named Entity Recognition use cases
4.   Load Dependencies
5.   Load Corpus
        -   Web Scraping using BeautifulSoup
        -   load to the drive
6.   Basic Named Entity (NE) tagging using NLTK
        -   Word Based
        -   Sentence Based
7.   More powerful package
        -   Stanford NLP NER
        -   Spacy
8.  The power of transformers
      - Bert-base-NER
      - French-camembert-postag-model
      - Tebyan-Arabic-Ner-Model
9.  Bidirectional LSTM 
    -   Inside–outside–beginning (tagging)
    -   data cleansing & validation
        -   English language
        -   Arabic & DARIJA
    -   Split data into train & test & validation sets 
    -   Build BiLSTM NER Model
    -   Train The Model
    -   Model Evaluation
        - Precision, Recall and F1-Score.
    -   How to improve Model Performance
    
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
            
            
### Want to see !! 
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.jupyter.org/github/ismailyou/named_entity_reco/blob/main/Named_Enitity_Extraction.ipynb)
### Launch it!
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ismailyou/named_entity_reco/blob/main/Named_Enitity_Extraction.ipynb)
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ismailyou/named_entity_reco/main?filepath=Named_Enitity_Extraction)
### Download as PDF
[![download !](https://img.shields.io/badge/Download-here-green)](https://drive.google.com/file/d/1zv4XWed2yxt1KSD5Cxth75Y9OWRWlwOY/view?usp=sharing)
        

    Our Team
        - JADID ISMAIL
        - LARHCHIM ZAKARIA
    Supervised By :    
        - Pr. ABDELHAK MAHMOUDI
        

