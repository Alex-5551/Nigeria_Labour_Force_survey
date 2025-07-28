
### Data Visualization of a sample of the Nigeria Labour Force
An exploratory data analysis on a sample from the Nigeria Labour Force survey conducted in 2024.



## Dataset
The sample was sourced from the NATIONAL BUREAU OF STATISTICS Nigeria Labour Force Survey Q2 2024
https://microdata.nigerianstat.gov.ng/index.php/catalog/152

## Preprocessing
Only columns partaining to the primary or main job of respondents were choosen. After that, rows with missing values where dropped. This was done in order to visualize actual and valid response and not imputed response. This reduced the shape from (44852, 205) to (1007, 19). 

The response that were encoded with numeric values was replaced with the actual string response, also the 'age' and 'hours_per_week' were convereted into range of values allowing for proper visualization.
columns answering the same question were also merged together. 

python libraries such as matplotlib, seaborn and plotly express were used for the visualization.
## Insights
1. The Typical full-time hours per week of a Nigeria is between 35-44 hours. 

2. There are more females in the professional fields than in agriculture, maunfacturing plants and the military.

3. Age distribution is as follows:
39-48: 28.7%

29-38:	23.9%

49-58:	17.9%

19-28:	17.7%

59-68:	5.6%

9-18:	5.3%

69-78:	0.6%

79-88:	0.19%

89+:     0.09%

4. The private sector aborbs more work force than any other sector. 
