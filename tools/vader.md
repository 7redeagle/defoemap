## [What is Vader:](https://github.com/cjhutto/vaderSentiment) 

VADER (Valence Aware Dictionary and sEntiment Reasoner) is an open source lexicon and rule-based sentiment analysis tool that is mainly used to analyze social media text. 

Vader Grade Score: The compound score is computed by summing the valence scores of each word in the lexicon, adjusted according to the rules, and then normalized to be between -1 (most extreme negative) and +1 (most extreme positive). This is the most useful metric if you want a single unidimensional measure of sentiment for a given sentence. Calling it a 'normalized, weighted composite score' is accurate.

⋅⋅ positive sentiment: compound score >= 0.05
⋅⋅ neutral sentiment: 0.05 > compound score > -0.05
⋅⋅ negative sentiment: compound score <= -0.05
