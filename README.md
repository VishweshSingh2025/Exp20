AIM
To study and implement real-world data analysis techniques using Python for analyzing COVID-19 pandemic data through data cleaning, preprocessing, aggregation, visualization, and trend analysis using Pandas, NumPy, and Plotly.

___________________________________________________________________________________________________

THEORY
Data analysis is the process of collecting, cleaning, transforming, and interpreting data to extract meaningful insights. In this experiment, a real-world COVID-19 dataset containing confirmed, recovered, and death cases across different countries and states was analyzed using Python libraries such as Pandas and NumPy. The dataset was first cleaned by removing unnecessary columns and converting data types into suitable formats such as datetime and integer values. New metrics like active cases were calculated using existing columns.
Further analysis was performed using grouping, filtering, sorting, and aggregation techniques to identify country-wise and state-wise case statistics. Interactive visualizations such as choropleth world maps were created using Plotly to represent the spread of confirmed and recovered cases globally. Time-series analysis was also performed to study daily growth trends. Such real-world data analysis helps in understanding disease spread patterns, comparing regions, and supporting decision-making through data-driven insights.
One-line explanation of functions used:
read_csv() – Loads the COVID dataset from a CSV file into a DataFrame.
head() – Displays the first few rows of the dataset.
drop() – Removes unwanted columns from the dataset.
info() – Shows column names, data types, and non-null counts.
astype() – Converts columns into required data types.
max() – Returns the maximum value, such as latest date.
groupby() – Groups data based on country, state, or date.
sum() – Calculates total values within grouped data.
reset_index() – Resets grouped index into normal columns.
value_counts() – Counts frequency of country/state occurrences.
nunique() – Returns number of unique values.
unique() – Displays all unique country or state names.
fillna() – Replaces missing values with specified values.
sort_values() – Sorts data in ascending or descending order.
iloc[] – Selects rows and columns using index positions.
choropleth() – Creates an interactive world map based on data values.
shape – Returns number of rows and columns in the dataset.

___________________________________________________________________________________________________

CONCLUSION
Thus, we successfully studied and implemented real-world COVID-19 data analysis using Python. We learned how to clean large datasets, compute active cases, analyze country-wise and state-wise statistics, perform date-wise trend analysis, and create interactive visualizations. This experiment demonstrated the practical use of Python in solving real-world analytical problems using data science techniques.
