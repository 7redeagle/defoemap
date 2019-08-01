---
title: Methods Used
permalink: /docs/methods-used/
redirect_from: /docs/index.html
---

## Methods

My original method involved me reading the entire text then assigning an emotion to each location visited. I then realized I needed a more quantifiable way to analyze emotions within the text so I added sentiment analysis tools to my list of resources.


I soon realized my earlier methods were too time consuming so I sought for a more machine-oriented way to streamline the process. My new method involved NER tagging the text (taken from Gutenberg) then locating the passages with those location tags and running those passages through two sentiment analysis tools before providing my own score of that passage. The two sentiment analysis tools used were Vader and Stanford sentiment analysis tool. Vader seems to provide a more positive rating while Stanford mostly gives out negative ratings to the passages. I then used ArcGIS to create a map for Defoe’s novels, which has different layers for each novel followed by separate layers for Vader, Stanford and my score of that novel. This method focused on locations mentioned in the text rather than the actual location the characters were in.


## My Current Method:
1. Download Stanford [NER Tool](https://nlp.stanford.edu/software/CRF-NER.shtml), [Vader](https://github.com/cjhutto/vaderSentiment#installation) and [AntConc](http://www.laurenceanthony.net/software/antconc/)
2. Set up the tools using the guides from the tool tab: [Stanford](https://github.com/IC97/Defoe-Map/blob/master/tools/stanford.md), [Vader](https://github.com/IC97/Defoe-Map/blob/master/tools/vader.md), and [AntConc](https://github.com/IC97/Defoe-Map/blob/master/tools/antconc.md)
3. Run text file of the novel or travel lit through the [Stanford NER tool](https://sites.google.com/site/endprojectmap/common/link) to tag the locations
4. Save tagged file then find the word "location" with a text editor. Save those passages according to their location onto a separate text file (pick passages with emotional value)
5. Or use [Alice's method](https://github.com/IC97/Defoe-Map/blob/master/methods/alice-method.md)
6. Run those passages through a Sentiment Tool (Vader and Stanford Sentiment Tool) according to the locations and save data on. Google Sheets (Use positive, neutral, and negative instead of numerical values)
7. Read the passages and supply my own emotional score. Save data on Google Sheets
8. Use [ArcGIS](https://www.arcgis.com/home/index.html) to map those data points with multiple layers corresponding to each novels and their sentiment analysis tool (Ex: Layer 1 could be Crusoe: My Score then Layer 2 is Crusoe: Vader and Layer 3 is Crusoe: Stanford
9. Repeat 3 - 8 with other novels and travel literature
10. (Optional) Use AntConc to collocate words (20L and 20R) next to the locations and draw a conclusion from those words.

## Abandoned Methods:

*Fusion Table:*
1. Run corpus through Vader or Stanford Sentiment Analysis
2. Save data and scores onto google sheets
3. Insert KML for shape of the bubbles
4. Make a fusion table from the spreadsheet
5. Play around with the map and the gradient of the bubbles (red for negative and green for positive)

*Scott Enderle's Method:*
1. Run corpus through Stanford NER Tool: Tags location within the text
2. Run that tagged file through a Sentiment Analysis Tool: Tagging the words next to a location tag with a sentiment tag
3. Or go to every sentence with location tag and assign a personal emotion to the passage
4. Use AntConc: Co-locate words that occurred next to a location, which should show the sentiment tag
5. Figure out the correlation of those emotion words next to location tags
