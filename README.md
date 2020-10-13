# Coursera_Capstone
<p> This project is part of the IBM Data Science Professional Certification provided by Coursera and its main objective is to apply data science concepts to analyze a real-world scenario. </p>

# 1.Introduction
<p>
One of the current concerns of the Seattle Department of Transportation (SDT) is to find solutions that can minimize the number of car accidents as well as fatalities, injuries and damages due to traffic accidents, in this context, all relevant information of accidents occurrences is recorded and maintained by the department for the access of all researchers. This data is necessary for identifying the locations and causes of crashes, for planning and implementing countermeasures, for operational management and control, and for evaluating highway safety programs and improvements.
</p>

## 1.1.Problem
</p>
The problem is that accidents have a different severity and implementation of countermeasures must be able to prioritize the implementation of solutions based on this. SDT classifies each of the registered collision with one of four categories, namely, Property Damage Only Collision, Injury Collision, Serious Injury Colision and Fatality Collision. This project intends to use these records to analyze all the collisions registered since 2004, in order to build a Machine Learning Model that will make it possible to classify the severity of a new collisions based on its characteristics.
</p>

<<<<<<< HEAD
## 1.2.Interest
<p>
The department may have more accurate and automatic accident classification and, consequently, programs that receive grant funding in the Seattle region have benefited from this information to define their action plan. Citizens of the city may be interested in wanting to know under what circumstances they are most vulnerable to getting involved in car collisions.
</p>

# 2.Data Understanding

<p>
The data set used in this project is available in a comma-separated values (CSV) file format and has been downloaded from <a href="https://data-seattlecitygis.opendata.arcgis.com/datasets/5b5c745e0f1f48e7a53acec63a0022ab_0?geometry=-122.326%2C47.592%2C-122.318%2C47.594" target="_blank">Seattle Open GeoData Portal</a> and includes all types of collisions since 2004 to Present. The dataset metadata was found at <a href="https://www.seattle.gov/Documents/Departments/SDOT/GIS/Collisions_OD.pdf" target="_blank"> Department of Transportation Seattle</a>.
The dataset contains 221738 rows/registers and 40 columns/fields. The dataset contains columns with 3 diferent type of values, float64, object and Int64.
</p>
=======
<p> To achieve the objective, the project applies data science concepts such as Machine Learning and Data Visualization under the CRISP-DM methodology, which is a model focused on communication, flexibility and iteration at each stage of the project to keep it on track right. The project was designed and structured based on 6 stages of the CRISP-DM methodology namely,Business understanding, Data understanding, Data preparation, Modeling, Evaluation and Implementation.</p>



# 2.Data Understanding

<p> The data set used in this project is available in a comma-separated values ​​(CSV) file format and has been downloaded from
 <a href="https://data-seattlecitygis.opendata.arcgis.com/datasets/5b5c745e0f1f48e7a53acec63a0022ab_0?geometry=-122.326%2C47.592%2C-122.318%2C47.594" target="_blank">Seattle Open GeoData Portal</a> and represents all collisions provided by SPD and recorded by Traffic Records since 2004 until present, this informations is updated weekly.
 </p>
<p> The data set metadata can be found at <a href="https://www.seattle.gov/Documents/Departments/SDOT/GIS/Collisions_OD.pdf" target="_blank"> Department of Transportation Seattle</a>.</p>

<p>The data set contains 221,389 records and 40 fields, the data contains categorical and continuous values and has some few columns with non-useless for our goal, such as the primary key, some other codes that represent relationships from another external data set.
</p>

<p>The model will be built with the SEVERITYCODE column as target, but during the analysis and visualization section of the independent variables, the SEVERITYDESC column will be used a lot, which is totally the same, but more descriptive.
</p>
>>>>>>> 074b640877933a1f59a21e51cec2c52e55408385
