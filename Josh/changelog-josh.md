**July 9, 2021** Created heatmap.

The primary heatmap features the correlation of each data query to the status, showing direct or inverse correlation from the data shown. Higher correlation statistics or a lighter color means that the patient is healthy if the data is a larger number. Inversely, lower correlation statistis or a darker color means that the patient is afflicted if the data is a smaller number. The latter two graphs show the correlation between individual queries only when the patient is healthy, which can be viewed in the first one, or afflicted, which can be viewed in the second one. 

General analysis can show that there is no strict correlation between a patient's status and any query. Therefore, it is difficult to state the status of a patient from only one column alone. However, there is a definitive correlation between queries like MDVP:Jitter(%) and NHR, where one is often a high number if the other one is a high number as well.

**July 12, 2021** Analyzed data.

While data measuring average points has the highest deviation, jitter measurements generally stay stagnant among various patients due to its low area of change. The only values that remain negative are the first spread, which categorizes the negative dimensionality of each case.

**July 13, 2021** Created random forest model.

The amount of trees included in the model is 100 by default, making the general accuracy of the forest tangible depending on the intervention of random size. Although general results are accurate, it would be effective to include other models that work in conjuction with the current one. Results convey a strong accuracy for data queries with an afflicted patient, but slight issues when it comes to healthy variants from normal cases. Greater jurisdiction in segregating deviant healthy patients and afflicted patients must be explored at a later date.
