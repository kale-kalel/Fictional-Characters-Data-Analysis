# Attribute-Analysis-of-Fictional-Human-Characters
## Overview
This project demonstrates data cleaning and visualization through analyzing the traits of fictional human characters. The dataset used can be found on Kaggle, [Super Hero Dataset (Comic Super Hero)](https://www.kaggle.com/datasets/aakashverma8900/superhero-api-dataset).

## Data Processing Summary
  1. Certain columns were dropped, and the remaining columns were renamed in a cleaner format.
  2. Nan values in numeric columns are filled in with their respective median.
  3. Numeric values are standardized to follow a specific format (e.g. Height in Feet, Weight in Kilograms).
  4. Nan values in non numeric columns are filled in with either 'Unknown' or 'None'.
     
## Data Visualization Techniques
  1. Matplotlib, Squarify, and Seaborn are utilized
  2. Demonstrated the use of pie chart, treemap, bar charts, and box plot

## Tools Used
  * Jupyter Notebook
  * Python
  * Pandas
  * Numpy
  * Matplotlib
  * Seaborn
  * Squarify

## Insights
The attribute analysis among fictional human characters revealed key findings:
  * **Top Performers Distribution**\
    Out of the 206 human characters in the dataset, only 92 characters (or 44.66%) are classified as top performers, scoring 100 out of 100 in certain attributes. This suggests that while there is a significant number of top-performing human
    characters, they still make up less than half of the population, indicating that only a select few possess superhuman abilities in the dataset.
  * **Intelligence**\
    Among the top performers, 13 individuals achieved a perfect score in intelligence. However the majority of the human population scores only ranges from medium to above average indicating that a hand few possesses peak human intellect.
  * **Strength**\
    In terms of strength, only 6 individuals are considered top performers, tying speed for the lowest number of top performing individuals. This suggests that super strength is rare among human characters. Furthermore, the majority of the
    population scores low to below average, indicating that humans are generally weak.
  * **Speed**\
    Similar to strength, only 6 individuals are classified as top performers in speed. Additionally, the majority of the population scores within the low to below average range, indicating that super speed is also rare among human characters.
    This suggests that humans are generally portrayed as slow, with only a few exceptions depicted with extraordinary speed.
  * **Durability**\
    Similar to intelligence, only 13 individuals are classified as top performers in terms of durability. However, the majority of the population falls within the below-average to above-average range, suggesting that humans are not as fragile as
    they may seem.
  * **Power**\
    With 35 top-performing individuals, power has the highest number of top performers. However, the majority of the population scores within the below-average to above-average range, suggesting that while some
    characters exhibit extraordinary power, most are depicted with more average to moderate levels of strength.
  * **Combat**\
    Ranking as the second highest attribute with 19 top performing individuals, a significant number of characters exhibit exceptional combat skills. However, the majority of the population scores within the average to above average range,
    suggesting that while they possess combat skills, most human characters are depicted as moderately skilled rather than elite.



