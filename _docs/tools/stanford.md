---
title: Stanford
permalink: /docs/stanford/
---

## [Stanford NER Tool:](https://nlp.stanford.edu/software/CRF-NER.html)

The tool will provide a tagged file of the text identifying words that fit under organization, location or person.

<img src="{{site.baseurl}}/img/stanford-ner.png">

1. Download Java 8 or later
2. Download zip file from [https://nlp.stanford.edu/software/CRF-NER.html](https://nlp.stanford.edu/software/CRF-NER.html)
3. Unzip and unpack zip files
4. Click on stanford-ner-3.9.1.jar (executable file) in the Stanford folde
5. Click on 'Classifier' then 'Load CRF from File' (CRF in classifiers folder)
6. Choose 'english.all.3class.distsim.crf.ser.gz' file
7. Choose the file you want to analyze or copy and paste text directly onto the tool
8. Click 'Run NER'
9. Save as Tagged File

## [Stanford Sentiment Tool:](http://corenlp.run/)

1. Go to [http://corenlp.run/](http://corenlp.run/)
2. Get rid of all the annotations except sentiment
3. Copy and paste your passage onto the box (make sure to use chunks not the entire text)
4. Click 'Submit' and record the data onto a spreadsheet

*Note: Stanford Sentiment Tool seems to mostly give a negative or neutral sentiment and rarely a positive one.*
