🎬 Netflix Movie Data Analysis
📌 Project Overview
This project performs a comprehensive Exploratory Data Analysis (EDA) on a dataset containing over 9,000 Netflix movies. The goal is to uncover patterns in content production, viewer popularity, and genre distribution using Python's data science ecosystem.

🛠️ Tech Stack
Language: Python

Libraries: Pandas, NumPy (Data Manipulation), Matplotlib, Seaborn (Visualization)

Environment: Jupyter Notebook

📊 Key Insights & Findings
Based on the analysis, the following conclusions were drawn:

Most Frequent Genre: Drama is the dominant genre on the platform, appearing in over 14% of the dataset.

Popularity Peak: Spider-Man: No Way Home holds the highest popularity score in the dataset.

Production Trends: The year 2020 marked the highest rate of movie filming/releases within this data.

High-Rated Content: Approximately 25.5% of the movies (6,520 rows) fall into the "Popular" category based on vote averages, with Drama again leading this segment.

🚀 Analysis Workflow
Data Cleaning: * Handled missing values and dropped irrelevant columns like Poster_Url and Overview.

Converted date strings into a standardized Year format.

Feature Engineering:

Categorized Vote_Average into descriptive labels: Popular, Average, Below Avg, and Not Popular.

Processed the Genre column using the .explode() method to ensure movies with multiple genres were accounted for individually.

Visualization:

Created count plots to show the distribution of genres.

Used histograms and bar charts to visualize the release trends over the years and popularity rankings.

📁 Repository Structure
Untitled.ipynb: The main Jupyter Notebook containing the source code and visualizations.

Netflix_Dataset.csv: (Make sure to include your data file or a link to it).

💡 Conclusion
The analysis highlights that while Netflix hosts a diverse range of genres, Drama remains their cornerstone for both volume and popularity. The data also reflects a significant surge in content production leading up to 2020.
