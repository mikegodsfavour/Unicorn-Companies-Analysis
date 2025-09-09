### **UNICORN COMPANIES ANALYSIS** ###

This is a Power BI project that analyzes unicorn companies — privately held startups valued at over $1 billion as of March 2022. The dataset includes essential details such as company name, valuation, funding, country, industry, city, continent, key investors, year founded, and unicorn year (date joined).

### Table of Content ###
- [Project Overview](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/edit/main/README.md#project-overview)
- [Project Scope](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/edit/main/README.md#project-scope)
- [Business Objective](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/edit/main/README.md#business-objective)
- [Document Purpose](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/edit/main/README.md#document-purpose)
- [Use Case](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/edit/main/README.md#use-case)
- [Skills Demonstrated](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/edit/main/README.md#skills-demonstrated)
- [Data Source](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/edit/main/README.md#data-source)
- [Data Connection Detail](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/edit/main/README.md#data-connection-detail)
- Data Profiling
- Data modelling
- Data Cleaning and Process
- Data Analysis and Insight
- Data Visualization
- Recommendation
- Conclusion

### Project Overview ###

This project aims to analyze the landscape of unicorn companies — privately held startups valued at over $1 billion as of March 2022 — using Power BI. By examining key data such as company valuation, funding, country, city, industry, selected investors, year founded, and year of achieving unicorn status, the project provides insights into investment trends, company growth patterns, and market opportunities.

**Through this analysis, stakeholders can better understand:**
- The historical trends of unicorn formation over time.
- The average time it takes companies to achieve unicorn status.
- The industries, countries, and investors driving the growth of unicorns.
This project equips investors, analysts, and business leaders with data-driven insights to make informed strategic decisions, identify high-potential sectors, and track startup ecosystem performance.

### Project Scope ###
The scope of this project is to analyze a dataset of privately held companies valued at over $1 billion as of March 2022 (unicorn companies). The analysis focuses on:
- Measuring return on investment (ROI) of unicorn companies.
- Calculating the average time it takes for companies to achieve unicorn status based on their year founded and Date Joined (unicorn year).
- Identifying the countries and cities with the highest concentration of unicorn companies.
- Analyzing the most active investors supporting unicorn growth.
- Using Power BI visualizations (bar charts, column charts, and line charts) to present key insights clearly and interactively.
The scope does not include mapping or geographical heatmaps, as the analysis focuses on temporal and categorical insights

### Business Objective ###
The objective of this project is to uncover key insights about unicorn companies (privately held startups valued at over $1 billion as of March 2022) to support strategic decision-making for investors, analysts, and business leaders.

### Document Purpose ###
This documentation serves as a guide for project stakeholders, providing insights into the project's objectives, data sources, data analysis, visualizations, and any other relevant information.

### Use Case ###
This Power BI project provides insights into unicorn companies — startups valued at over $1 billion as of March 2022 — that can drive improvement across investment decision-making, market analysis, and strategic planning. Different stakeholders within the startup and investment ecosystem can use these findings to enhance their respective functions.
**Key stakeholders who could benefit from this analysis include:**
- Investment Managers
  - Can use insights on return on investment (ROI) and average time to unicorn to guide funding allocation.
  - Identify promising companies and industries with high growth potential.
- Business Strategists & Analysts
  - Can track trends in unicorn formation over time to predict future startup success cycles.
  - Use industry and investor insights to shape competitive strategies.
- Startup Founders & Executives
  - Gain awareness of the timelines and patterns associated with achieving unicorn status.
  - Benchmark their growth trajectory against historical trends.
- Venture Capital & Private Equity Firms
  - Analyze investor participation patterns to assess market competition.
  - Focus investments in locations and industries showing consistent unicorn emergence.
This analysis serves as a strategic tool for optimizing investments, spotting emerging opportunities, and improving decision-making in the high-growth startup ecosystem.

### Skills Demonstrated ###
This project showcases the following skills:
- Power BI Development
  - Designed interactive dashboards using line charts, bar charts, and column charts.
  - Created calculated measures and KPIs using DAX to analyze ROI, average time to unicorn, and investor contributions.
- Data Analysis & Insight Generation
  - Extracted meaningful insights on unicorn formation trends, ROI distribution, and investor activity.
  - Interpreted historical timelines to assess changes in unicorn growth speed over time.
- Data Cleaning & Transformation
  - Processed raw dataset to ensure consistency in fields such as company name, valuation, funding, year founded, and date joined.
- Business Intelligence Reporting
  - Translated data findings into actionable insights for investors, business strategists, and startup founders.
  - Presented complex information in a clear, concise, and visual manner to support decision-making.
 
### Data Source ###
The dataset for this project is sourced from [Maven Analytics website](https://app.mavenanalytics.io/datasets?search=Unicorn), designed specifically for practice purposes. The project utilizes a dataset containing information on unicorn companies (privately held startups valued at over $1 billion as of March 2022).
The dataset was downloaded from the Maven Analytics platform and is provided in CSV format. It consists of one main table with 1,074 rows and 10 columns.
The columns include:

- Company – Name of the unicorn company.
- Valuation – Current valuation of the company in billions of US dollars.
- Funding – Total amount of funding raised by the company in US dollars.
- Country – Country where the company was founded or is headquartered.
- City – City where the company is located.
- Industry – Sector or market in which the company operates.
- Selected Investors – Key investors who have funded the company.
- Year Founded – The year the company was established.
- Date Joined – The year the company achieved unicorn status (valuation above $1 billion).
- Continent – The continent where the company is located.
This dataset provides a comprehensive view of unicorn companies, including their valuations, funding details, industries, and investors, which makes it suitable for performing trend analysis, ROI evaluation, and growth insights in Power BI.

### Data Connection Detail 
In Power BI, connecting to an CSV file involves specifying the location of the CSV file and defining the data import settings. Here are the steps taken in data connection in Power BI.

1. Open Power BI Desktop
- Launched Power BI Desktop on computer.

