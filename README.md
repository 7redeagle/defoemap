<p style="text-align: center;"><strong>Plotting Defoe's Adventure Novels: 18th Century Adventure and Travel Literature Emotion Map Project</strong></p>

My research project was an emotion map of Daniel Defoe’s adventure novels. The novels used were Robinson Crusoe (1719), Captain Singleton (1720), and Colonel Jack (1722) . The map was meant to show the emotions associated with locations mentioned (not necessarily visited) in these books . The inspiration for this project was an emotion map created by [Christian Nold](http://stockport.emotionmap.net/background.htm). His maps represented the emotions, opinions and dialogue of the local population. The map was drawn from a pile of drawings made by the people in the city to portray their perception of the place they live in. I was fascinated by how he managed to combine this static and hyper-accurate medium with something as abstract and ambiguous as human emotions. I wanted to create something similar to Christian Nold’s map: a world map of the 18th-century drawn from the passages of Defoe’s novels.

My new method involved NER tagging the text (taken from Gutenberg) then locating the passages with those location tags and running those passages through two sentiment analysis tools before providing my own score of that passage. The two sentiment analysis tools used were Vader and Stanford sentiment analysis tool. Vader seems to provide a more positive rating while Stanford mostly gives out negative ratings to the passages. I then used ArcGIS to create a map for Defoe’s novels, which has different layers for each novel followed by separate layers for Vader, Stanford and my score of that novel. This method focused on locations mentioned in the text rather than the actual location the characters were in. 

I made two maps:  one for Defoe's novels and one for the travel literature. The maps had several layers, each corresponding to a novel, and shades corresponding to the emotions. For example, green for positive, red for negative, and gray for neutral. I want to see if Defoe's emotional interpretation of the location in his novel matched up with those of the non-fiction travel books. I mainly focused on England’s international relations with other countries such as France. 

**Research Question:** How does Defoe describe these locations and how his descriptions evoke a negative, positive or neutral emotion?

**Table of Contents:** 1. Methods 2. Tools 3. Maps

<p style="text-align: center;"><strong>Resources</strong></p>

* [Gutenberg:](https://www.gutenberg.org/wiki/Main_Page) OCR Text
* [Stanford NER Tool:](https://nlp.stanford.edu/software/CRF-NER.html)Named Entity Recognizer tool for tagging locations
* [Vader Sentiment Analysis Tool:](https://github.com/cjhutto/vaderSentiment)Tool for analyzing emotional valence of text 
* [Stanford Sentiment Analysis Tool:](https://stanfordnlp.github.io/CoreNLP/)Tool for analyzing emotional valence of text 
* [ArcGIS: Mapping Software](https://www.arcgis.com/home/index.html)
* [AntConc: Text Analysis](http://www.laurenceanthony.net/software/antconc/)
* [Google Sheets:] Data Collection
