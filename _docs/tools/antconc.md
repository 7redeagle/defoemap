---
title: AntConc
permalink: /docs/antconc/
---

## [What is AntConc:](http://www.laurenceanthony.net/software/antconc/)

AntConc is a program capable of analyzing and extrapolating patterns in electronic text. With AntConc, you can identify the pattern of a specific word or look at the differences between corpora.

![alt text](https://github.com/IC97/Defoe-Map/blob/master/images/antconc.png "AntConc")

### AntConc Collocation:

As I continued working on this project, I eventually started to branch off into a secondary project involving AntConc. I found out that if I collocate (finding the most frequent words around a certain word) a location word then I could get peripheral words that provide a general idea of the author’s description of that location. For example, in Robinson Crusoe, when I did a collocation search for the word  ‘Africa,’ the most frequent words to appear were: vulgarly, enterprises, productions, leopards, sailors, desert, tigers, shipwrecked, perished, lions, skins, misfortunes. These words painted Africa as a wild and dangerous place that was also very profitable. Another example was the location word ‘Sallee’ which produced the results: Turkish, Turks, rovers, moors, war, emperor, devoured, prisoners. This provided a very negative illustration a place controlled by the Turks who were barbarians that took prisoners. This is supported 18th-century British sentiments towards the Turks. These are the steps I took for the AntConc collocation:

1. Download and Install [AntConc](http://www.laurenceanthony.net/software/antconc/)
2. Start AntConc
3. Choose the file you want to analyze from the 'File' menu
4. Click the 'open' button
5. Click on the 'collocates' tab
6. Choose the window span for you search (I prefer 20L and 20R)
7. Enter word into the search box
8. Click ‘Start’ button
9. Pick the words that jump out at you in the top 30 (sorted by stat)
10. Record that data onto the google sheets containing emotional readings
