# Table of contents
- [Objective](#objective)
- [Metrics used](#metrics-used)
- [Data preparation](#data-preparation)
- [Exploratory data analysis overview](#exploratory-data-analysis-overview)
- [Datasets](#datasets)

<div id="objective"></div>

## Objective

To uncover insights on what types of Netflix contents that are enjoyed and well-received by their viewers

<div id="metrics-used"></div>

## Metrics used

* How enjoyable the content is determined by the average weighted rating and total votes casted by IMDB users
* The types of contents refers to MPAA ratings, genres, original content, etc
* Other factors that also contribute to how enjoyable the content is includes country, release year, duration, etc

<div id="data-preparation"></div>

## Data preparation
1. Merge main Netflix dataset with original Netflix dataset
2. Delete duplicated records and records with many missing information
3. Missing records are replace with 0 or No info
4. Merge IMDB datasets to the merged Netflix dataset
5. Repeat setp 2 and step 3 again
6. Export final dataset to local machine for checking purposes

<div id="exploratory-data-analysis-overview"></div>

## Exploratory data analysis overview

Nine different insights were obtained from doing the exploratory data analysis on Netflix and IMDB data.  
Correlation matrix, lmplot, violinplot, barplot and wordcloud are used to illustrate the findings and insights.  
` The_Netflix_EDA_journey.pptx ` contains the summarized version of the EDA while the full version and source code is located in ` Netflix_EDA_Liyana.ipynb `

<div id="datasets"></div>

## Datasets

All datasets used except the IMDB datasets are located under ` datasets ` folder.    
The IMDB datasets can be retrieved here:  
https://drive.google.com/drive/folders/15_u_4zOmunuxz8j8YnJzQkG849VPWLdy?usp=sharing
