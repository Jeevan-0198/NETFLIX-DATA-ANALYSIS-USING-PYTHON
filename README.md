# NETFLIX-DATA-ANALYSIS-USING-PYTHON
## OBJECTIVE
The objective of the project is to analyze and visualize the given Netflix data using Pandas and Matplotlib. Additionally, this project answers various questions based on project requirements, providing valuable business insights and supporting future development.
## DATASETS
<a herf="">Datasets</a> used here doesn't refelct original datasets of netflix.  
Includes fileds such as Show_Id,Category,Title,Director,Cast,Country,Release_Date	Rating,Duration,Type,Description.
## EXPLANATION
### Libraries Used:
- **Pandas**(Pandas used for Data Cleaning),
- **Seaborn**(Seaborn used for Data Visualisation)
### Data Cleaning
- First, I removed duplicates using the drop_duplicates() function.
- Next, I identified, visualized, and removed null values to ensure data completeness.
- I extracted and separated the Date column to facilitate better analysis and visualized year-wise data trends.
- I identified unique values in relevant columns as part of the data cleaning process to ensure consistency and accuracy.
### Visualisation
- I made some of the visualisation for better understanding of datas
   - I visualise null values using heatmaps of seaborn.  
  ![image](https://github.com/user-attachments/assets/d627a0d6-5ce3-418e-a31f-25308670c410)   
   - I visualise year-wise release of movies using vertical bar charts.
  ![image](https://github.com/user-attachments/assets/c7bc29c4-0b47-4e06-b188-a0ac348472bc)  
   - I visualise categories-wise data using Horizontal bar charts.  
  ![image](https://github.com/user-attachments/assets/98d8cd44-5fcd-4e4e-b6f1-276b517bce0c)

### Filters
Various filtering functions were used to refine and extract relevant data efficiently.  
**Examples:**
- to_datetime(): Used to convert and extract date and time information.
- isin() and str.contains(): Applied to filter specific strings within the dataset.
- Logical operators (&, |, ~): Used to create complex filtering conditions for data selection.
## KEY QUESTIONS ANSWERED BY THE CODE
1)How can we identify and remove duplicate records in a Netflix dataset using Pandas?
2)What techniques can be used to handle missing values in a dataset, and how do they impact data analysis?
3)How can we extract and analyze the release year of Netflix content using Pandas' to_datetime function?
4)What is the distribution of Netflix content across different categories, and which category appears most frequently?
5)How can we filter Netflix data to find specific titles, genres, or content released in a particular year?
6)Which country has produced the highest number of Netflix movies and TV shows?
7)How can we identify the most common directors and actors in Netflix’s catalog?
8)What filtering techniques can be applied to analyze content trends based on ratings and duration?
9)How can sorting and grouping operations help in understanding Netflix’s content distribution by country and category?
10)What insights can be derived by analyzing the duration of Netflix content across different categories?

## Conclusion:
This Netflix Data Analysis project successfully cleaned and processed the dataset to extract key insights. Duplicate and null values were handled, date-based trends were analyzed, and filtering techniques helped explore content distribution. The analysis provided insights into popular genres, country-wise contributions, and category-wise distribution.

## Way Forward:
**To enhance the project:**  
- Add interactive visualizations for deeper trend analysis.
- Implement sentiment analysis on viewer reviews.
- Develop a content recommendation system using ML.
- Automate data pipelines for real-time analysis.
    
    
  
     
 



