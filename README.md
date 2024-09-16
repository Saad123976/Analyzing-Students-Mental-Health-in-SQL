**Analyzing Students' Mental Health in SQL**

**Introduction**

This project aims to analyze the mental health of students based on survey data, focusing on different aspects of psychological well-being. The dataset includes various indicators related to mental health and the students' stay status. The objective is to calculate and compare average mental health scores across different stay categories to identify patterns or trends.

**Methodology**

**Data Import and Initial Inspection:**

Imported data from students.csv for analysis.
Initial query to retrieve all data fields to understand the structure and contents.

**Data Filtering and Aggregation:**

Filtered data to include only students who are part of the international program (inter_dom = 'Inter').
Calculated average scores for three mental health indicators (PHQ, SCS, AS) grouped by stay status.
Used SQL functions to round the averages for better readability and comparison.

**Data Sorting and Grouping:**

Grouped results by stay status to aggregate average scores.
Ordered the results by stay status in descending order for easy comparison.

**Results**

**Average Scores by Stay Status:** The query results display average scores for psychological well-being indicators (PHQ, SCS, AS) based on whether students stayed in the program or not.

**Comparison:** The output allows for a comparison of mental health metrics between different stay categories, highlighting differences in well-being scores.

**Conclusions**

The analysis provides insights into mental health trends among students in the international program. By calculating average scores for different mental health indicators, we can identify areas needing attention and potentially tailor support strategies to improve student well-being. The results can guide further research or interventions aimed at enhancing mental health support for students.



