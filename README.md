# Financial & Sales Performance Dashboard with Power BI
A data analysis and visualization practice built in Power BI using a public data set from [chandoo.org](https://chandoo.org/wp/)

The goal was to independently replicate and personalize the **Financial & Sales Dashboard** demonstrated by [Chandoo in his YouTube video](https://youtu.be/i3AR0gt9SHA?si=suMojILCSCgra5D2), applying my own approach to data modeling, DAX calculations, and visualization techniques to highlight KPIs, track target attainment, and evaluate employee performance.

## Project Description
The dataset consists of four Excel sheets:
-  `Actual`: Company sales data.
-  `Targets`: Company sales targets.
-  `dimPeople`: Employee information (name, picture, team).
-  `Calendar`: Calendar table for time-based analysis.
The raw dataset contained inconsistencies such as duplicate employee pictures, and table orientation issues. These were corrected in Power Query before building the data model.

## KPI Calculations using DAX
Measures include:
- Total Sales
- Sales Target
- Variance (absolute and %)
- YTD Sales
- YTD Target Sales
- YTD Variance (absolute and %)

## Highlights
The Dashboard includes:
- **Financial Overview**: Total Sales vs. Target Sales with variance tracking.
- **Trend Analysis**: Monthly financial performance across 14 months.
- **Target Attainment**: Visualization of actual vs. expected results over time.
- **Employee Performance**: Individual breakdown about sales figures and variance analysis.

## Tools & Technologies

- **Power BI**: Dashboard design and visualization.
- **Power Query**: Data cleaning and transformation.
- **DAX**: KPI calculations and performance metrics.
- **Excel**: Original dataset source.
