# Assignment 4: Python

Link to datasets: https://www.ontario.ca/page/public-sector-salary-disclosure

### What software did you use to create your data visualization?
The software used to visualize is Python.

### Who is your intended audience?
The primary intended audience for this visualization is Human Resources (HR) professionals within various sectors. These professionals can use the data to benchmark salaries and ensure competitive and fair compensation practices within their organizations. 

### What information or message are you trying to convey with your visualization?
The goal of the visualization is to convey the average salaries and salary distributions across different sectors. This information will help HR professionals understand how salaries vary by sector and identify potential areas where their organization might need to adjust compensation to remain competitive. The bar chart highlights the average salary for quick comparison.

### What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?
Design Principles:
* Substantive Principles:
    * Accuracy and Clarity: Ensured that the data is accurately represented without misleading manipulations.
    * Relevance: Focused on sectors and salaries, which are directly relevant to HR professionals.

* Perceptual Principles:
    * Color Coding: Used a consistent color palette (e.g., viridis) to help distinguish different sectors and avoid confusion.
    * Labeling: Clear labels and titles were added to ensure the audience can easily understand what the axes represent and what the visualization is about.

* Aesthetic Principles:
    * Visual Appeal: Chose an aesthetically pleasing color palette and ensured that the plots were not cluttered.
    * Balance and Spacing: Ensured proper spacing between bars and elements to make the plot easy to read.

* Application:
    * Bar Chart: Used to show the average salary by sector with clear, distinct bars for each sector.

### How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?

* Ensuring Reproducibility:
    * Code Sharing: Provided the complete Python code using libraries such as Pandas, Matplotlib, and Seaborn to clean, process, and visualize the data. This ensures that anyone with access to the dataset and the code can reproduce the visualizations.
    * Documentation: Included comments and explanations within the code to clarify each step of the data processing and visualization process.

* Impact if Not Reproducible:
    * Lack of reproducibility would undermine the credibility and reliability of the visualization. Stakeholders would not be able to verify the results or adapt the visualization for their specific needs.

### How did you ensure that your data visualization is accessible?

* Ensuring Accessibility:
    * Readable Fonts: Used readable font sizes and sans-serif fonts for better readability.
    * Color Contrast: Chose color palettes that are colorblind-friendly and ensured sufficient contrast between different elements.
* ImprovementsL
    * To improve on the accessibility of this visualization, I could include Alt Text and Descriptions. This would provided descriptions and alternative text for visualizations when shared in reports or presentations.

### Who are the individuals and communities who might be impacted by your visualization?
* Impacted Individuals and Communities:
    * HR Professionals: Directly impacted as they use the data for decision-making regarding salaries and benefits.
    * Employees and Job Seekers: Indirectly impacted as salary adjustments and fairness in compensation practices can affect their earnings and job satisfaction.
    * Executives and Business Leaders: Use the data to understand competitive salary benchmarks and budget allocations.


### How did you choose which features of your chosen dataset to include or exclude from your visualization?
* Feature Selection:
    * Included Features:
        * Sector: To categorize the data by different sectors.
        * Salary: As the primary variable of interest to analyze compensation.

* Excluded Features:
    * Non-relevant Columns: Columns like 'Last name', 'First name', 'Benefits', 'Employer', 'Job title', and 'Year' were excluded as they were not relevant to the core objective of analyzing average salaries by sector.

### What ‘underwater labour’ contributed to your final data visualization product?
* Data Cleaning: Effort was spent cleaning the data, including removing non-numeric characters from the 'Salary' column, handling missing values, and ensuring data types were consistent.
* Code Development: Writing, testing, and debugging the Python code to ensure it correctly processed the data and generated the desired visualizations.
