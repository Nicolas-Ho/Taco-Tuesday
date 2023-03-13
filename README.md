# Taco-Tuesday

##### Author: Nicolas H

##### Date: March 13, 2023

##### Disclaimer : This project is only to be taken as a mean of showcasing some Tableau skills through the representation and analysis of LeBron James's relationship with Tacos. The analysis is not to be taken too seriously as it integrates low sample size for some of the data and willingly ignore a lot of factors that could explain the variations in LeBron's performances. 

##### [Tableau Dashboard](https://public.tableau.com/shared/JTTC2KJCP?:display_count=n&:origin=viz_share_link)

#### <div class='tableauPlaceholder' id='viz1678736292296' style='position: relative'><noscript><a href='#'><img alt='LeBron 2019-2023 Overview ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;JT&#47;JTTC2KJCP&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='path' value='shared&#47;JTTC2KJCP' /> <param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;JT&#47;JTTC2KJCP&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en-US' /></object></div>                

## Scenario
During Summer 2019 NBA superstar LeBron James posted an Instagram story of him and his family enjoying tacos and following the Mexican tradition of eating tacos on tuesdays. The video went viral and for the entire summer every tuesday a new video of him would be posted, thus creating a new tradition for LeBron and his family. The purpose of this project is to analyse the relationship of LeBron and tacos and how it translates to his performances in NBA games.

#### The viral video 

https://www.youtube.com/watch?v=UFOHYRZAu3I

## Data Preparation

To conduct this analysis I needed two different dataset : all in game statistics from LeBron since the start of his Taco Tuesday tradition and the number of Taco Bells in NBA cities, the leading Taco restaurant chain in the US.

To gather all the data from LeBron's games from 2019 to 2023 I used the website https://www.basketball-reference.com/ which is renown for its quality. I pulled all his stats for the 4 NBA seasons since 2019 and merged all the data by using SQL queries.

For the taco bell locations I used the official website https://locations.tacobell.com/index.html and pulled the data for all 30 NBA cities. I then cleaned it and prepared it for Tableau by adding a few necessary columns.

## Analysis


-  [2019-2023 Performance](#2019-2023-performance)
-  [Performance on tuesdays](#tuesday-performance)
-  [LeBron and Taco restaurants](#lebron-taco)
-  [Summary](#summary)


### 2019-2023 Performance

d

