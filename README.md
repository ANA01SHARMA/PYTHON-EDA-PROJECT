# PYTHON-EDA-PROJECT
🛣️ Urban Street Network Analysis – Road Segment Insights from City Data
Welcome to the Urban Street Network Analysis repository! This project focuses on extracting actionable insights from a city's road segment dataset by analyzing street characteristics such as length, directionality, responsible authority, and classification. Using Python and data visualization tools like Pandas, Seaborn, and Matplotlib, this repository answers key urban planning questions with both statistical and visual rigor.

📁 Dataset Overview
The dataset includes the following key columns:

ST_NAME: Name of the street.

LENGTH: Length of each road segment.

Shape_Length: Geometric length of the segment (GIS-based).

CLASS: Street classification code.

RESPONSIBL: Department or authority responsible for the segment.

ONEWAY: Directionality of the road (B, T, TF, etc.).

🎯 Objectives
This project is organized around five analytical objectives:

1. Street Frequency Analysis
Which streets appear most frequently in the dataset?

Columns Used: ST_NAME

Methods: value_counts(), head()

Visualization: Bar plot

Insight: A small number of streets account for a large number of segments, indicating main arteries or highly divided roads.

2. Longest Road Segments
What are the top 10 longest individual road segments in the city?

Columns Used: ST_NAME, LENGTH

Methods: sort_values(), head(), NumPy stats

Visualization: Lollipop chart

Insight: Longest segments likely represent highways or major connectors crucial for city logistics and traffic flow.

3. Authority vs. Segment Length
Are longer streets assigned to specific responsible authorities?

Columns Used: RESPONSIBL, LENGTH

Methods: groupby(), mean(), describe()

Visualization: Strip plot with mean overlay

Insight: Different agencies specialize in different types of roads, revealing responsibility-based infrastructure division.

4. One-Way vs Both-Way Traffic
What is the count of one-way vs both-way streets?

Column Used: ONEWAY

Methods: value_counts()

Visualization: Bar chart using Set2 palette

Insight: Most roads support two-way traffic, but one-way segments exist in high-traffic areas for flow optimization.

5. Correlation Among Length, Shape Length, and Class
Are there any correlations between length, shape length, and street class?

Columns Used: LENGTH, Shape_Length, CLASS

Methods: corr(), heatmap()

Visualization: Annotated heatmap

Insight: LENGTH and Shape_Length are strongly correlated; CLASS is weakly correlated, implying it's based on broader criteria than just size.

🧪 Technologies Used
Python 3.10+

Pandas

NumPy

Matplotlib

Seaborn

Jupyter Notebook
