# Assignment 4: Tableau Public

* Link to datasets: https://www.ontario.ca/page/public-sector-salary-disclosure
* Link to Tableau Public: https://public.tableau.com/app/profile/adrienne.lloren/viz/shared/7QQDTS66C

### What software did you use to create your data visualization?
The software used to visualize is Tableau Public.

### Who is your intended audience?
The intended audience includes:
* Policymakers and government officials interested in understanding sector-wise salary patterns.
* Public sector employees and unions who want transparency in salary trends.
* Researchers, journalists, and advocacy groups analyzing public expenditure.
* Taxpayers looking for insight into how public funds are distributed across sectors.

### What information or message are you trying to convey with your visualization?
The visualization aims to:
* Show the average salary across various sectors in the public sector.
* Highlight disparities or consistencies in salary distribution by sector.
* Provide a clear overview of which sectors command the highest and lowest average salaries, prompting further analysis of sector-specific roles.

### What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?
* Substantive:
    * Clarity of Purpose: The visualization directly focuses on average salaries by sector, avoiding unnecessary complexity.
    * Relevance: Only the average salary metric and sector names are included, as they are most pertinent to the analysis.

* Perceptual:
    * Color Encoding: Used a colour to differentiate each sector.
    * Legibility: Ensured that all sector names and salary figures are readable, even for long sector names.

* Aesthetic:
    * Consistency: Applied a clean, professional design with consistent font and layout styles.
    * Visual Hierarchy: Used larger fonts for key figures (e.g., average salary) and smaller text for sector names, guiding the audience’s focus. For instance, a bar chart was chosen because it effectively conveys comparisons between sectors.

### How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization?
* Reproducibility Measures:
    * The raw data, cleaning, and transformation steps were fully documented in Python code.
    * The merged and cleaned dataset was exported and shared in a reproducible format (CSV), allowing others to replicate the visualization.

* Impact of Using Tableau Public:
    * Tableau Public provides an interactive and shareable platform but lacks programmatic reproducibility.
    * To mitigate this, detailed documentation of the steps taken in Tableau (e.g., filters applied, aggregation methods, color scales) could be created to accompany the visualization.

### How did you ensure that your data visualization is accessible?
* Color Accessibility: Used a colorblind-friendly gradient scale.
* Interactive Elements: Incorporated tooltips in Tableau to provide additional information about each sector without overwhelming the main visualization.
* Font and Labeling: Ensured labels and text are appropriately sized for readability across devices.
* Tableau Public Hosting: Made the visualization freely accessible online, ensuring a wide audience can access it without requiring proprietary software.

### Who are the individuals and communities who might be impacted by your visualization?
* Impacted Groups:
    * Public sector employees: The visualization provides transparency and could influence discussions about pay equity.
    * Policymakers: Insights might guide decisions about resource allocation and budget adjustments.
    * Advocacy Groups: Data could be used to highlight disparities or advocate for specific sector reforms.
    * Taxpayers: Provides clarity on how public funds are distributed in terms of salaries across sectors.

* Ethical Considerations:
    * Care was taken to avoid individual-level salary data to protect privacy.
    * The visualization avoids bias by focusing on averages rather than extremes or outliers.


### How did you choose which features of your chosen dataset to include or exclude from your visualization?
* Included Features:
    * Sector and Average Salary were chosen as they provide the clearest and most impactful insights for the intended purpose.

* Excluded Features:
    * Redundant details like individual names or salaries were excluded to maintain clarity and focus on broader trends.

The choice was driven by the need to create a clear, concise visualization that answers specific audience questions.

### What ‘underwater labour’ contributed to your final data visualization product?
* Data Cleaning:
    * Standardizing sector names to resolve inconsistencies (e.g., “CollegesÂ ” → “Colleges”).
    * Addressing encoding issues and normalizing column names for ease of use.
* Data Aggregation:
    * Calculating average salaries by sector from raw, unaggregated datasets spanning multiple years.
* Tool Learning:
    * Navigating Tableau Public features like tooltips, filters, and custom color scales.
* Iteration:
    * Experimenting with different chart types, color schemes, and layouts to find the most effective design.


