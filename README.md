# **UNICORN COMPANIES ANALYSIS** 

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
- [Data Profiling](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/edit/main/README.md#data-profiling)
- [Data modelling](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/edit/main/README.md#data-modelling)
- [Data Cleaning and Process](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/edit/main/README.md#data-cleaning-and-process)
- [Data Analysis and Insight](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/edit/main/README.md#data-analysis-and-insight)
- [Data Visualization](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/edit/main/README.md#data-visualization)
- [Recommendation](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/edit/main/README.md#recommendation)
- [Conclusion](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/edit/main/README.md#conclusion)

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
The dataset was downloaded from the Maven Analytics platform and is provided in Excel format. It consists of one main table with 1,074 rows and 10 columns.
The columns include:

- **Company** – Name of the unicorn company.
- **Valuation** – Current valuation of the company in billions of US dollars.
- **Funding** – Total amount of funding raised by the company in US dollars.
- **Country** – Country where the company was founded or is headquartered.
- **City** – City where the company is located.
- **Industry** – Sector or market in which the company operates.
- **Selected Investors** – Key investors who have funded the company.
- **Year Founded** – The year the company was established.
- **Date Joined** – The year the company achieved unicorn status (valuation above $1 billion).
- **Continent** – The continent where the company is located.
This dataset provides a comprehensive view of unicorn companies, including their valuations, funding details, industries, and investors, which makes it suitable for performing trend analysis, ROI evaluation, and growth insights in Power BI.

### Data Connection Detail 
In Power BI, connecting to an Excel file involves specifying the location of the Excel file and defining the data import settings. Here are the steps taken in data connection in Power BI.

1. Open Power BI Desktop
- Launched Power BI Desktop on computer.
![](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/blob/main/Unicorn%20pictures/Power%20BI%201.png)

2. Get Data
- Clicked on the "Blank report" tab in the Power BI Desktop.
- Clicked on the "Home" tab in the Power BI Desktop.
- Selected "Get Data" to initiate the data import process
![](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/blob/main/Unicorn%20pictures/Get%20Data.png)

3. Choose Excel and Specify the File Location
- In the "Get Data" window, selected "Excel Workbook" as the data source.
- Navigated to the location where the Excel file is stored.
- Selected the Excel file I want to import and clicked "Open."
![](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/blob/main/Unicorn%20pictures/Load%20Data.png)

4. Load and Transform Data
- Click on “Load Data” → this will import the dataset directly into Power BI Desktop, where you can start building and viewing your visuals (reports, dashboards, charts).
![](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/blob/main/desktop.png)


- Click on “Transform Data” → this will open the Power Query Editor, where you can clean, transform, and shape your dataset (remove nulls, fix data types, split columns, etc.) before loading it into Power BI Desktop.
![](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/blob/main/transform.png)

### Data Profiling
Before analysis, the dataset was profiled in Power Query Editor to understand its structure and quality.
Key Profiling Tasks Included:

- **Data Structure**
  - Dataset contained 1,074 unicorn company records as of March 2022.
  - Dataset consisted of 10 fields, including: Company, Valuation, Funding, Country, City, Continent, Industry, Investors, Year Founded, and Date Joined.
    
- **Column Analysis**
  - Company: Categorical, name of each unicorn company.
  - Valuation: Numeric (after cleaning). Originally stored as Text with unwanted characters. Cleaned and stored as Whole Number. Missing or unknown values were replaced with 0.
  - Country / City / Continent: Categorical – used for geographical or regional grouping (though not visualized with maps in this project).
  - Industry: Categorical – grouped companies by sector.
  - Investors: Text field – often contained multiple investors per company. For analysis, only selected investors were considered.
  - Year Founded: Year field – used to calculate company age.
  - Date Joined: Date/Year field – the year the company achieved unicorn status.

- **Missing Value Check**
  - Some fields such as Funding and Investors had missing or incomplete entries.
  - Where values were unknown (e.g., certain funding values), they were replaced with 0.
  - For text fields like Investors, missing values were left blank to avoid distorting results.

- **Data Type Validation**
  - Valuation converted to Decimal Number.
  - Funding converted to Whole Number.
  - Year Founded and Date Joined converted to Date/Year data types


## Data modelling
The dataset used for this analysis consisted of a single flat table containing all necessary attributes of unicorn companies (Company, Valuation, Funding, Country, City, Continent, Industry, Investors, Year Founded, and Date Joined).
![](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/blob/main/Unicorn%20pictures/Modeling.png)

Because all the required fields were already included in one table, there was no need to create relationships or build a complex data model.
The data was directly connected and prepared in Power Query Editor, then loaded into Power BI Desktop for analysis and visualization.

## Data Cleaning and Process
In Power BI, data cleaning was performed using Power Query Editor, which provides versatile tools to shape and transform data before loading it into the Power BI model. This step was crucial to ensure data integrity, quality, consistency, and accuracy.

After conducting data profiling, the dataset was generally well-structured and consistent, but several cleaning steps were required to prepare it for analysis:
- Valuation Column: Removed symbols ($, B, M, commas) and converted to Decimal Number. Missing value was replaced with 0.
- Funding Column: Removed unwanted characters, converted to Whole Number. Missing/unknown values were replaced with 0.
- Investors Column: Left in Text format as it often contained multiple investors. Missing values left blank.
- Date Fields: Converted Year Founded and Date Joined to proper Date/Year types for time-based calculations.
No new calculated columns were created in Power Query, as the dataset already contained all necessary fields for analysis.

**DAX Measures Created**
The following DAX measures were developed in Power BI to support detailed analysis:

   - **Total Unicorns** → Counts the total number of unicorn companies.

*DAX code for calculating Total Unicorn*

`Total Unicorn = DISTINCTCOUNT(Unicorn_Companies[Company])`

   - **Total Funding Raised** → Calculates the total funding across all unicorns.

*DAX code for calculating Total Funding Raised*

`Total Funding Raised = 
VAR TotalFunding = SUM('Unicorn_Companies'[Funding])
VAR InBillions = DIVIDE(TotalFunding, 1000000000)
RETURN
"$" & FORMAT(InBillions, "#,##0") & " B"`

   - **Total Valuation** → Calculates the combined valuation of all unicorns.
 
*DAX code for calculating Total Valuation*

`Total Valuation (B) = 
VAR TotalValuation = SUM('Unicorn_Companies'[Valuation])
VAR InBillions = DIVIDE(TotalValuation, 1000000000)
RETURN
"$" & FORMAT(InBillions, "#,##0") & " B"`

   - **Return on Investment (ROI)** → Measures the ratio of valuation to funding for each company.

*DAX code for calculating Return on Investment (ROI)*

`Return On Investment(ROI) = DIVIDE(SUM(Unicorn_Companies[Valuation]) -SUM(Unicorn_Companies[Funding]), SUM(Unicorn_Companies[Funding]), 0)`

   - **Average ROI** → Calculates the average ROI across all unicorns.

*DAX code for calculating Average ROI*

`Average(ROI) = DIVIDE(SUM(Unicorn_Companies[Valuation]) - SUM(Unicorn_Companies[Funding]), SUM(Unicorn_Companies[Funding]))`
  - **Time to Unicorn (Years)** → This calculates the number of years it took each individual company to become a unicorn.
    
*DAX code for calculating Total Time to Unicorn (Years)*

`Time to Unicorn (Years) = 
VAR AvgTime =
    AVERAGEX(
        'Unicorn_Companies',
        YEAR('Unicorn_Companies'[Date Joined]) - 'Unicorn_Companies'[Year Founded]
    )
RETURN
FORMAT(ROUND(AvgTime,0), "0") & " Years"`
  - **Average Time to Unicorn (Years)** → This calculates the average number of years across all unicorn companies.

 *DAX code for calculating Average Time to Unicorn (Years)*
     
`Average Time to Unicorn Year = AVERAGEX(VALUES(('Unicorn_Companies'[Date Joined])), CALCULATE(AVERAGEX( Unicorn_Companies,YEAR('Unicorn_Companies'[Date Joined]) - 'Unicorn_Companies'[Year Founded])))`

These measures formed the foundation of the analysis and were used to build interactive visuals such as bar charts, line charts, and KPI cards.
  
## Data Analysis and Insight

**1. Which unicorn companies have had the biggest return on investment (ROI)?**

This question seeks to identify the unicorn companies that generated the highest return on investment (ROI), a critical measure of profitability and growth efficiency. ROI is an important performance metric because it shows how much value a company has created compared to the funding it received. By highlighting companies with the highest ROI, this analysis uncovers the most financially efficient unicorns, helping to understand which startups turned investor capital into the greatest value.

The analysis was carried out by calculating ROI for each company as:
 
   ``ROI = (Valuation – Funding Raised)/ Funding Raised``
	​

This metric measures how much value (valuation) a unicorn generates beyond the funding it has received. Companies with higher ROI demonstrate stronger financial performance and more efficient use of capital, while those with lower ROI may indicate weaker growth relative to their funding.

![](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/blob/main/Unicorn%20pictures/Biggest%20Return%20On%20Investment%20By%20The%20Unicorn%20Companies.png)

**Insights from the Analysis**

The analysis revealed that Zongmu Technology recorded the highest Return on Investment (ROI), achieving many times its funding in valuation. Zihaiguo and Zipline followed closely, both showing ROI values significantly above their funding, which indicates strong investor returns and efficient capital utilization.

Other companies in the top 10 with outstanding ROI performance include Zilch, Zocdoc, Zume, Ziroom, Zuoyebang, Zwift, and Zopa. Each of these companies demonstrated the ability to generate valuations that far exceeded their initial funding, signaling robust business models and market demand.

These findings highlight how certain unicorn companies have been able to leverage their funding efficiently to achieve high valuations, thereby delivering exceptional returns to investors.

**2. How long does it usually take for a company to become a Unicorn? Has it always been this way?**

This question seeks to understand the average time it takes companies to achieve Unicorn status (valuation of $1 billion or more) from the year they were founded. The calculation was done by subtracting each company’s founding year from the year it achieved Unicorn status. This measure is referred to as Time to Unicorn (Years), while the overall trend across all companies is measured using Average Time to Unicorn (Years).

![](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/blob/main/Unicorn%20pictures/Average%20Time%20to%20Unicorn%20Trend.png)

**Insights from the Analysis**

The analysis shows that, on average, unicorn companies take about 7 years to achieve this milestone. This reflects the typical growth cycle and highlights how quickly companies scale from start-up stage to billion-dollar valuation.

To explore whether this pattern has remained constant over time, a line chart was used to visualize Average Time to Unicorn by Year Joined. The results indicate a clear trend:

In earlier years (around 2008-2010), companies often took 9–10 years to reach unicorn status.

In more recent years (2020–2022), many companies achieved unicorn valuation in just 6-7 years.

This trend suggests that the time to unicorn has been decreasing over the years, reflecting faster market adoption, increased venture capital availability, and technology-driven growth cycles.

**3. Which countries have the most Unicorns?**

This question explores the geographic distribution of unicorn companies by country, aiming to identify nations that dominate the global unicorn landscape. Analyzing unicorn counts by country helps reveal where innovation ecosystems are thriving and which regions attract the most venture capital investment.

The measure Total Unicorns (calculated using DISTINCTCOUNT(Company)) was used to count the number of unique unicorn companies in each country. A bar chart visualization was employed to compare countries side by side, making it easy to identify the leading hubs.

![](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/blob/main/Unicorn%20pictures/Top%20Countries%20With%20The%20Most%20Unicorn.png)

**Insights from the Analysis**

The analysis revealed that:

- United States leads with the highest number of unicorns, reflecting its strong startup ecosystem, large venture capital network, and technology-driven markets.

- China follows as the second-largest hub, driven by its rapid digital adoption and government-backed funding initiatives.

- Other countries such as India, United Kingdom, and Germany also ranked among the top contributors, showcasing growing startup ecosystems.

These insights highlight how unicorn creation is not evenly distributed across the globe but is instead concentrated in innovation-heavy economies with access to capital, talent, and market opportunities.

**4. Are there any cities that appear to be industry hubs?**

This question investigates whether certain cities stand out as key hubs for unicorn companies, attracting a high concentration of startups across industries. Identifying such cities provides insights into the role of urban innovation ecosystems, access to funding, infrastructure, and talent pools.

The measure Total Unicorns (DISTINCTCOUNT(Company)) was used to count the number of unicorns in each city. A bar chart visualization was applied to display the top-performing cities, making it clear which locations are most attractive to unicorn companies.

![](https://github.com/mikegodsfavour/Unicorn-Companies-Analysis/blob/main/Unicorn%20pictures/Top%20City%20As%20Unicorn%20Hubs.png)

**Insights from the Analysis**

The analysis revealed that:

- San Francisco emerged as the top unicorn hub, largely driven by its proximity to Silicon Valley and access to global venture capital.

- New York and Beijing and ollowed closely, reflecting China’s thriving innovation and government-backed tech ecosystem.

- Other cities such as Shanghai and London also ranked highly, underscoring their role as global financial and startup centers.

These results show that unicorn creation is highly clustered in innovation-driven urban hubs, where supportive ecosystems enable startups to scale faster and secure higher valuations.

**5. Which investors have funded the most unicorns?**

This question seeks to identify the top investors who have played the largest role in supporting unicorn companies. Investors are a critical part of the unicorn ecosystem, as their funding decisions directly influence which startups achieve billion-dollar valuations.

The analysis focused on the “Investors” column of the dataset, where companies often have multiple backers. To address this:

- The data was processed to split and clean multiple investors per company.

- Each investor’s contribution was then counted to determine how many unique unicorns they have funded.
  
A Column chart visualization was used to display the Top 10 investors by number of unicorns funded

**Insight from Your Analysis**

The analysis revealed that Y Combinator emerged as the top investor, funding the highest number of unicorns. Following closely were Zeev Ventures, Yabeo Capital, Yinhong Equity Investment, YL Ventures, and York Capital Management.

These investors have consistently backed multiple unicorn startups, highlighting their strong ability to identify and support high-growth companies early on. The prominence of Y Combinator, in particular, demonstrates the critical role of startup accelerators in nurturing unicorns.

## Data Visualization


## Recommendation


## Conclusion

