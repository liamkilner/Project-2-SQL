# Project-2-SQL

# Team Members

Liam Kilner https://github.com/liamkilner/Project-2-SQL/edit/main/README.md

Victoria Wiest https://github.com/victoriawiest/MIST4610Project2

# Description of the dataset:
Our dataset contains information about COVID-19 in a worldwide perspective. We obtained our dataset from: https://www.kaggle.com/datasets/imdevskp/corona-virus-report. This set contains a variety of dimensions with varying data types. It includes information such as Country and Region, which is a data type string. It also includes information such as Number of Confirmed Cases, Number of Deaths,  Number of Recoveries, Number of Active Cases, Number of New Cases, Number of New Deaths, and Number of New Recoveries. These are all part of the data type interval. Lastly, it includes Death Rate and Recovery Rate, included in the data type number(decimal). Overall, this dataset has a variation of different dimensions that help us understand the spread of COVID-19 across the world.

# Question 1
Create a heatmap of the count of COVID-19 cases across the world. What countries are poorest at controlling their COVID-19 death rate?
Importance : 
Countries that are deemed to be the poorest at controlling their COVID-19 death rate will require more support in responding to ongoing pandemic. Furthermore, these countries more than likely have issues combating other diseases as well so they would require more support and guidance from WHO. As the data is analyzed it will help other countries in fighting COVID-19 as well. It should be noted that there are some differences amongst countries such as access to health care and COVID-19 protocol that may make it difficult for countries to control their death rate in an efficient manner.

![Graph 1](https://github.com/liamkilner/Project-2-SQL/assets/141340172/9e89002f-6601-45c3-8195-1d44d1cd706a)

![Graph 2](https://github.com/liamkilner/Project-2-SQL/assets/141340172/b0d22ec2-27f5-4425-ba66-33d4380c9411)

Our first graph is a heatmap of COVID-19 cases around the world. In that graph, we found that the COVID-19 cases tended to be higher in larger, more populated countries such as the United States, China, and India. We also included a bar graph that illustrates the count of COVID-19 deaths per hundred cases, the death rate, for various countries around the world. COVID-19 deaths per hundred cases was significantly higher in Yemen, whereas the rates for the other countries tended to be more similar. This data is interesting because both high and low resourced countries had high death rates, not just low resourced countries like we originally suspected.

# Question 2
What regions, according to the World Health Organization, have the highest recovery rate?
Importance :  
It is important to capture what regions have the highest recovery rate, so that other regions are able to model what measures they took to help their population recover from COVID-19 faster. This analysis is important to ensure a swift response is possible for similar future diseases that may arise. 

![Graph 3](https://github.com/liamkilner/Project-2-SQL/assets/141340172/1358a6e1-8eec-41e6-91c7-d159a6d28e04)

Our second graph is a waffle graph illustrating the recovery rates in various regions around the globe. We found that the recovery rate was highest in Europe with Africa and the Americas falling behind it. The regions with the lowest recovery rates were the Western Pacific, Eastern Mediterranean, and South-East Africa. This data shows us a lot because although Europe had a large spread of cases, according to our heat map, they also had a significantly higher recovery rate. On the other hand, South-East Asia suffered with the lowest recovery rate, which is highly likely due to it being the epicenter of the pandemic. 

# Manipulations applied to the data set for analysis:
We did not have to manipulate or alter any data.

# Tableau Packaged Workbook:
The packaged workbook containing the visualizations shown above is attached to this repository.
