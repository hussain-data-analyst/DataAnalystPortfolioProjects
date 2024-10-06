# Crimes Against Women in India: A 15-Year Trend Analysis (2001-2015)

## Project Overview

This project analyzes crime data from 2001 to 2015, focusing on crimes against women across different states and districts in India. The aim is to uncover trends and patterns in various types of crimes, such as **Rape**, **Kidnapping and Abduction**, **Dowry Deaths**, and more. Insights were drawn using Python for data analysis and visualization, and Tableau was used for interactive dashboards.

### Objectives
* Conduct year-wise analysis to observe trends and patterns in crimes against women over the years 2001-2015.
* Perform state-wise and district-wise analysis to identify regions with the highest crime rates.
* Investigate the most prevalent crimes within states and compare crime trends across regions.
* Provide clear and impactful visualizations for better understanding and decision-making.

---

## Dataset

The dataset was sourced from [data.gov.in](https://data.gov.in) and contains crime data related to women for the years 2001-2015. The dataset includes the following features:

* **STATE/UT**: The State or Union Territory.
* **DISTRICT**: Districts within each state.
* **Year**: The year of recorded crimes.
* **Crimes**: Various categories of crimes, including:
  * Rape
  * Kidnapping and Abduction
  * Dowry Deaths
  * Assault on women with intent to outrage modesty
  * Insult to modesty of women
  * Cruelty by Husband or his Relatives
  * Importation of Girls
  * Total Crimes

---

## Tools & Libraries Used

* **Python** for data analysis and cleaning.
  * **Pandas**: Data manipulation.
  * **NumPy**: Handling numerical operations.
  * **Matplotlib** and **Seaborn**: Data visualization.
* **Jupyter Notebook**: Used for coding and documenting the project.

---

## Project Workflow

### 1. **Data Cleaning**
* Imported year-wise datasets, handled null values, removed redundant information, and standardized column names.
* Merged all datasets into a clean, comprehensive file for analysis.

### 2. **Data Exploration & Analysis**
* **Year-wise Analysis**: Trends and patterns across various crimes over the years.
* **State-wise Analysis**: Identified top 10 states with the highest and lowest crime rates.
* **District-wise Analysis**: Found the top 5 districts with the highest number of crimes.

### 3. **Visualizations**
* Created bar charts, line charts, and heatmaps to visualize:
  * Yearly trends for different types of crimes.
  * State-wise and district-wise distribution of crimes.

---

## Key Insights

### Overall Crime Trends
* Total crimes increased from 2001 to 2014 but showed a decline in 2015.
* **Cruelty by Husband and His Relatives** had the highest number of cases, showing an increasing trend but decreased after 2014.
* **Assault on Women with Intent to Outrage Modesty** showed a significant increase between 2012 and 2014.
* **Kidnapping and Abduction** and **Rape** cases were on a consistent rise but also decreased after 2014.
* **Dowry Deaths** and **Insult to Modesty of Women** remained relatively constant with minor variances.
* **Importation of Girls** cases remained constant over the years.

### Correlation Insights (From Correlation Matrix)
* **Rape and Assault on Women with Intent to Outrage Modesty** are highly correlated (**0.899**), indicating that states with high rape cases also tend to have high assault cases.
* **Kidnapping & Abduction** shows strong correlations with **Rape** (**0.723**) and **Dowry Deaths** (**0.860**), implying these crimes often occur in regions where these crimes are already prevalent.
* **Cruelty by Husband or His Relatives** is strongly correlated with **Total Crimes** (**0.930**), making it a significant contributor to overall crime rates.
* **Insult to Modesty of Women** and **Assault on Women with Intent to Outrage Modesty** are moderately correlated (**0.641**), suggesting that these crimes frequently occur together.
* **Dowry Deaths** and **Kidnapping & Abduction** are also highly correlated (**0.860**), indicating a possible link in regions where these crimes are reported.
* **Importation of Girls** has a weak correlation with other crimes, indicating that this crime type is relatively isolated from other forms of violence against women.

### Top 10 States with the Highest Crimes  
  1. Uttar Pradesh  
  2. Andhra Pradesh  
  3. West Bengal  
  4. Rajasthan  
  5. Madhya Pradesh  
  6. Maharashtra  
  7. Assam  
  8. Delhi  
  9. Kerala  
  10. Odisha  

### Top 10 States/UTs with the Least Crimes  
  1. Meghalaya  
  2. Goa  
  3. Mizoram  
  4. Puducherry  
  5. Andaman & Nicobar Islands  
  6. Sikkim  
  7. Nagaland  
  8. Dadra & Nagar Haveli  
  9. Daman & Diu  
  10. Lakshadweep  

### Top 10 Districts with the Highest Crimes  
  1. Murshidabad (West Bengal)  
  2. 24 Parganas South (West Bengal)  
  3. 24 Parganas North (West Bengal)  
  4. Hyderabad City (Andhra Pradesh)  
  5. Nadia (West Bengal)  
  6. Cyberabad (Andhra Pradesh)  
  7. Karimnagar (Andhra Pradesh)  
  8. Mumbai Commr. (Maharashtra)  
  9. West Godavari (Andhra Pradesh)  
  10. Lucknow (Uttar Pradesh)

---

## Challenges Faced

* Data inconsistencies across years, such as district name variations, required careful cleaning.
* Creating visualizations that clearly reflected the scale and severity of crimes across different regions.

---

## Conclusion

This project provides a detailed analysis of crimes against women in India from 2001-2015, highlighting significant trends and regions where crimes are most prevalent. These insights can aid policymakers and law enforcement agencies in formulating strategies to address and reduce crime rates, particularly in high-crime regions.
