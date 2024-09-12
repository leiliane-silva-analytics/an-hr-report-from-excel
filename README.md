# HR Analytics Report Project

## Objective

The purpose of this project is to help an organization and its leaders improve their teams by providing a strategic overview through an HR Analytics Report. This report delivers valuable insights into employee data, enabling data-driven decision-making.

## Data Source (Extraction)
Originally, the raw data for this project was obtained in the form of three CSV files:
- Main file: 46 columns and 51.6k rows
- Second file: 4 columns and 165k rows
- Third file: 11 columns and 40.5k rows
#### Customized Data Source:
To maintain company confidentiality, 85% of the rows were eliminated. Additionally, dates, salaries, names, references, locations, and areas were modified to create a sample dataset for demonstration purposes.

## Data Processing and Cleaning
Several steps were taken to prepare before the visualizations and analysis. Due to the size of the raw data, it was split into two files:
1. Dataset Processing (Transforming):
 - Removed null and duplicate values.
 - Identified and corrected spelling errors; assigned appropriate data types.
 - Created 16 auxiliary tables to convert classified information into rows to support visualizations.
 - Generated a new table with 44 columns to standardize the data, correctly classify information, and unify the three datasets into a single table summarizing all data per employee.
 - Developed various Pivot Tables from this main table to extract essential data for the final report.
   
    ```Formulas used: VLOOKUP, IF, AND, OR, IFERROR, DATEDIF, SUMIF.```

2. Dataset for KPI Report (Loading):
- The summaries generated from the Pivot Tables were copied for this file, where the charts were created.
- The ideia is to created a report file to visualize the insights while maintaining HR confidentiality of the raw information.
		
## Visualization
### Creating charts, insights and reports
Several charts and visualizations were used to gain insights into the employee data through descriptive analysis. Some key insights from the analysis include:
- Pie Chart: Displayed employee profiles based on different characteristics, such as Age Range, Ethnicity, and Gender, to analyze diversity.
- Column Chart: Showed data trends throughout the year, including headcount, hiring, layoffs, extra hours, and turnover.
- Bar Chart: Provided a comparative analysis between two variables.
- Speedometer Graph: Offered a quick overview of the percentage of extra hours worked and how much it deviates from acceptable levels.
- Extra Hour Report: Enabled detailed analysis with area managers to understand the reasons for extra hours and strategize for reduction.
  
    ```Tools Used: VBA, Pivot tables```
  
    ```Formulas used: VLOOKUP, SUMIF, IFERROR, etc.```
  
## Conclusion
This HR analytics dashboard provides crucial insights into employee data that can help organizations make better decisions based on descriptive visual data to improve various strategic areas.
- Diversity: Analyzing employee characteristics.
- Equity Pay: Comparing average salaries.
- Well-being / Cost Management: Monitoring and managing extra hours.

[![Assista ao vídeo no YouTube](https://img.youtube.com/vi/AANSngyQcGc/maxresdefault.jpg)](https://www.youtube.com/watch?v=AANSngyQcGc)
