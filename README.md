# World Happiness Report 2019 - Exploratory Data Analysis

This project is an Exploratory Data Analysis (EDA) of the **World Happiness Report 2019**. I developed this project to practice.

## Project Objective
The goal of this analysis was to identify the key drivers of global happiness and to apply advanced data manipulation techniques with Pandas and sophisticated visualization principles using the Matplotlib Artist Layer.

## Key Features & Analyses
- **Data Cleaning:** Standardizing feature names, managing index structures (Country-based indexing), and validating data integrity.
- **Correlation Analysis:** Investigating the relationship between GDP per capita, Social Support, and the overall Happiness Score.
- **Hypothesis Testing:** Created a scatter plot with a linear regression line (using Numpy's Polyfit) to visualize the trend between economic wealth and subjective well-being.
- **The "Anatomy of Happiness":** Calculated the **Residual** (Dystopia Residual) to isolate and visualize the impact of unmeasured factors (cultural, social, or psychological) on the final score.
- **Comparative Visualization:** Developed a side-by-side comparison of the Top 10 and Bottom 10 countries using Stacked Bar Charts, featuring custom color palettes and optimized layouts following Tufte’s principles.

## Key Findings
- **GDP per capita** remains the strongest predictor of happiness, but the analysis reveals that for the top-ranking nations, happiness levels often exceed what GDP alone would suggest, driven by high Social Support scores.
- The **Residual** component is significantly larger in the Top 10 nations compared to the Bottom 10, highlighting the importance of "intangible" social assets in highly happy societies.
