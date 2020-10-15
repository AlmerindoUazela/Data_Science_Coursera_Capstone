# Coursera_Capstone
<p> This project is part of the IBM Data Science Professional Certification provided by Coursera and its main objective is to apply data science concepts to analyze a real-world scenario. </p>

# 1.Introduction
<p>One of the current concerns of the Seattle Department of Transportation (SDT) is to find
solutions that can minimize the number of traffic accidents, as well as deaths, injuries and
damage from traffic accidents, in this context, all relevant information about the occurrence of
accidents are registered and maintained by the department for access by all researchers. This
data is necessary for the planning and implementation of countermeasures, operational control
and for evaluating road safety programs and improvements.</p>

<p>Accidents have different severities and the implementation of countermeasures must be able
to take this aspect into account in order to prioritize their projects, therefore, the process of
classifying the severity of accidents must be carried out as accurately as possible. This project
intends to analyze all collisions registered since 2004, in order to build a Machine Learning
Model to predict the classification of the severity of new accidents based on their characteristics
with 100% accuracy</p>

## 1.2.Interest
<p>
The department may have more accurate and automatic accident classification and, consequently, programs that receive grant funding in the Seattle region have benefited from this information to define their action plan. Citizens of the city may be interested in wanting to know under what circumstances they are most vulnerable to getting involved in car collisions.
</p>

# 2.Data Understanding

<p>
The data set used in this project is available in a comma-separated values (CSV) file format and has been downloaded from <a href="https://data-seattlecitygis.opendata.arcgis.com/datasets/5b5c745e0f1f48e7a53acec63a0022ab_0?geometry=-122.326%2C47.592%2C-122.318%2C47.594" target="_blank">Seattle Open GeoData Portal</a> and includes all types of collisions since 2004 to Present. The dataset metadata was found at <a href="https://www.seattle.gov/Documents/Departments/SDOT/GIS/Collisions_OD.pdf" target="_blank"> Department of Transportation Seattle</a>.
The dataset contains 221738 rows/registers and 40 columns/fields. The dataset contains columns with 3 diferent type of values, float64, object and Int64.
</p>
