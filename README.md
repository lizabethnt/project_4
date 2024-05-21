# project_4
UO Data Bootcamp | Project 4
For Project 4, we will work with our group to solve, analyze, or visualize a problem using machine learning (ML) with the other technologies we’ve learned. Here are the specific requirements:

**Find a problem worth solving, analyzing, or visualizing.**
Question: 
What ecological factors are correlated with demographic outcomes such as income?
Can we predict GDP or life expectancy of a country by some of its ecological footprint factors?
Which countries consume more resources than they produce?

Dataset: 
https://www.kaggle.com/datasets/jainaru/global-ecological-footprint-2023

**Data Summary**
    * Country: Name of the country.
    * Region: Geographic region to which the country belongs.
    * SDGi: Sustainable Development Goals index.
    * Life Expectancy: Average life expectancy in years.
    * HDI: Human Development Index, a composite index measuring life expectancy, education, and per capita income.
    * Per Capita GDP: Gross Domestic Product (GDP) per capita.
    * Income Group: Income group classification (e.g., LI for Low Income, UM for Upper Middle Income).
    * Population (millions): Population of the country in millions.
    * Cropland Footprint: Ecological footprint of cropland activities, measured in global hectares per person.
    * Grazing Footprint: Ecological footprint of grazing activities, measured in global hectares per person.
    * Forest Product Footprint: Ecological footprint of forest product activities, measured in global hectares per person.
    * Carbon Footprint: Ecological footprint of carbon emissions, measured in global hectares per person.
    * Fish Footprint: Ecological footprint of fish consumption, measured in global hectares per person.
    * Built-up land: Ecological footprint of built-up land, measured in global hectares per person.
    * Total Ecological Footprint (Consumption): Total ecological footprint of consumption, measured in global hectares per person.
    * Cropland: Biocapacity of cropland, measured in global hectares per person.
    * Grazing land: Biocapacity of grazing land, measured in global hectares per person.
    * Forest land: Biocapacity of forest land, measured in global hectares per person.
    * Fishing ground: Biocapacity of fishing ground, measured in global hectares per person.
    * Built-up land: Biocapacity of built-up land, measured in global hectares per person.
    * Total biocapacity: Total biocapacity, measured in global hectares per person.
    * Ecological (Deficit) or Reserve: The difference between total ecological footprint and total biocapacity, indicating whether the country has an ecological deficit (negative value) or reserve (positive value).
    * Number of Earths required: The number of Earths that would be required if everyone lived like the average person in the country.
    * Number of Countries required: The number of countries with the same biocapacity that would be required if everyone lived like the average person in the country.
    * These columns provide insights into the ecological impact of each country in terms of resource use and waste generation, as well as its biocapacity to support these activities.

**Then:**
* Use machine learning (ML) with the technologies we’ve learned.
* You must use Scikit-learn and/or another machine learning library.
* Your project must be powered by a dataset with at least 100 records.
* You must use at least two of the following:
    * Python Pandas
    * Python Matplotlib
    * HTML/CSS/Bootstrap
    * JavaScript Plotly
    * JavaScript Leaflet
    * SQL Database
    * MongoDB Database
    * Google Cloud SQL
    * Amazon AWS
    * Tableau


Requirements: 
Requirements
**Data Model Implementation (25 points)**
- A Python script initializes, trains, and evaluates a model (10 points)
- The data is cleaned, normalized, and standardized prior to modeling (5 points)
- The model utilizes data retrieved from SQL or Spark (5 points)
- The model demonstrates meaningful predictive power at least 75% classification accuracy or 0.80 R-squared. (5 points)

**Data Model Optimization (25 points)**
- The model optimization and evaluation process showing iterative changes made to the model and the resulting changes in model performance is documented in either a CSV/Excel table or in the Python script itself (15 points)
- Overall model performance is printed or displayed at the end of the script (10 points)

**GitHub Documentation (25 points)**
- GitHub repository is free of unnecessary files and folders and has an appropriate .gitignore in use (10 points)
- The README is customized as a polished presentation of the content of the project (15 points)

**Group Presentation (25 points)**
- All group members speak during the presentation. (5 points)
- Content, transitions, and conclusions flow smoothly within any time restrictions. (5 points)
- The content is relevant to the project. (10 points)
- The presentation maintains audience interest. (5 points)

