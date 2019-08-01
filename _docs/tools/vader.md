---
title: Vader
permalink: /docs/vader/
---

## [What is Vader:](https://github.com/cjhutto/vaderSentiment)

VADER (Valence Aware Dictionary and sEntiment Reasoner) is an open source lexicon and rule-based sentiment analysis tool that is mainly used to analyze social media text.

Vader Grade Score: The compound score is computed by summing the valence scores of each word in the lexicon, adjusted according to the rules, and then normalized to be between -1 (most extreme negative) and +1 (most extreme positive). This is the most useful metric if you want a single unidimensional measure of sentiment for a given sentence. Calling it a 'normalized, weighted composite score' is accurate.

* positive sentiment: compound score >= 0.05
* neutral sentiment: 0.05 > compound score > -0.05
* negative sentiment: compound score <= -0.05

![alt text](https://github.com/IC97/Defoe-Map/blob/master/images/vader-sample.png "Vader Sample")

## Vader Setup:
1. Read How to Guide: [Sentiment Analysis for Exploratory Data Analysis](https://programminghistorian.org/en/lessons/sentiment-analysis#exploring-text-with-sentiment-analysis)
2. Update Python on my laptop to Python 3.6. and download the required dependencies
3. Update PIP and download Msgpack then Twython
4. Download NLTK plus options
5. Set up according to the guide
6. Use Sublime Text: Edit document in Sublime. Save as file.py then run through python3.6. Open terminal in that folder. Type python3.6 ./filename.py
7. Or run in Sublime: [Link Python 3.6 to Sublime](https://gist.github.com/zaemiel/4fbd8b5125fda7a140be). Build System. Click 'Tool' then 'Build'

## Pros:
* Simple to setup
* Computationally efficient
* Performs well on short passages

## Cons:
* Not as accurate on larger chunks of text
* Mainly used to analyze social media tweets not passages from 18th century novels
* Tends to give either a positive or negative reading but almost never a neutral one

