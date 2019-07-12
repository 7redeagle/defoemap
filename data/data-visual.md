## Data Visualization (Unrelated to Main Project)

My chart and graph both look at the number of novels published from 1710 to 1800, using [END data](https://github.com/earlynovels/end-dataset) I focused on their titles as a generic identification of their genre. A novel’s genre, during the 18th century, seems to already be in its title so I wanted to see how many novels of each genre were published every decade within the timeframe I’m focusing on. The five labels are adventure, letters, life, romance and history. I cleaned the data with openrefine, clustering similar titles together then made a spreadsheet with the number of novels of each category within 1710 to 1800. I noticed that most novels that would fall into the romance genre were titled as a “History of a []” or the “Historical Romance of [].” Romance novels tend to overlap with history. The Other category are those novels that do not include any of the previously mentioned words in their titles. 

1. Created excel spreadsheet of only the full titles (merged 243$a and 245$b with Openrefine) and the publishing dates. 

2. In openrefine, I clustered together the novels with similar titles then numeric facet only 1700-1800. 

3. Then I filtered them for each category. I also numeric facet the publishing dates and recorded the number of novels for each category in each decade from 1710 - 1800. 

4. Finally, made a chart/line graph and pie chart. 

5. Use the filter in spreadsheet to figure out the number of books with these categories in their titles out the total number of books published from 1710-1800.

![Title Chart](https://github.com/IC97/Defoe-Map/blob/master/images/title-chart.png)

![Title-Pie](https://github.com/IC97/Defoe-Map/blob/master/images/title-pie.png)
