# Data-visualization-project
University Rankings Report
Dataset Description
The dataset, university_data.csv, contains information on university rankings
across various countries. It includes 100 entries with the following columns:
• university_name: Name of the university (object, 100 non-null)
• country: Country where the university is located (object, 100 non-null)
• num_students: Number of students (object, 97 non-null, with commas as
thousand separators)
• total_score: Overall ranking score (float64, 100 non-null)
• teaching: Teaching quality score (float64, 100 non-null)
• research: Research quality score (float64, 100 non-null)
• citations: Citation impact score (float64, 100 non-null)
Shape: 100 rows, 7 columns
Missing Values:
• num_students: 3 missing values
• All other columns: 0 missing values
The num_students column is stored as a string with commas (e.g., "20,152")
and requires conversion to numeric format for quantitative analysis.
Key Findings
1. Top 5 Universities by Total Score:
o Harvard University: 96.1
o California Institute of Technology: 96.0
o Massachusetts Institute of Technology: 95.6
o Stanford University: 94.3
o Princeton University: 94.2
These universities, all from the United States, dominate the top
rankings based on total score.
2. Average Scores by Country:
Below is a summary of average scores for selected countries (full table
available in the dataset analysis):
o United States of America: Total Score: 74.9, Teaching: 67.8,
Research: 70.8, Citations: 85.8
o United Kingdom: Total Score: 79.7, Teaching: 74.9, Research:
77.9, Citations: 88.2
o Switzerland: Total Score: 81.5, Teaching: 78.5, Research: 84.0,
Citations: 91.5
The UK and Switzerland show strong average performance, often
surpassing the US in specific metrics like teaching and citations.
3. Country with the Most Universities:
o United States of America: 49 universities
The US accounts for nearly half of the universities in the dataset,
indicating its significant presence in global higher education
rankings.
Insights from Visualizations
1. Average Total Score by Country (Bar Plot)
[Insert Visualization: avg_total_score_by_country.png]
The bar plot illustrates the variation in average total scores across
countries. Countries like Switzerland and the United Kingdom exhibit
higher average scores, suggesting a concentration of high-quality
institutions, while countries with fewer universities (e.g., China, Japan)
show more variability. The United States, despite having the most
universities, has a slightly lower average due to a broader range of
performance levels.
2. Teaching vs Research Scores (Scatter Plot)
[Insert Visualization: teaching_vs_research.png]
The scatter plot reveals a strong positive correlation between teaching and
research scores across universities. Top-performing institutions (e.g.,
Harvard, Stanford) cluster in the upper-right quadrant, indicating
excellence in both areas. However, some universities excel in one metric
over the other, suggesting diverse strengths. Country-specific patterns
emerge, with US and UK universities widely distributed, reflecting varied
institutional focuses.
