# Unicorn Companies Data Visualization

"Unicorn" is a term used in the venture capital industry to describe private companies with a valuation over $1 billion. In this project, a Tableau dashboard is created to visualize the unicorns data as of March 2022. 

## Dashboard
View my [Dashboard on Tableau Public](https://public.tableau.com/views/UnicornCompanies_16523546443960/DashboardUnicorn?:language=en-US&:display_count=n&:origin=viz_share_link) to interact with the data.

Here's what it looks like:
![Alt text](./Dashboard%20Unicorn.png?raw=true "Dashboard snapshot")

## Data
The data was downloaded from [Maven Analytics](https://www.mavenanalytics.io/data-playground?page=1&pageSize=5). It contains each unicorn company's current valuation, funding, country of origin, industry, select investors, and the years they were founded and became unicorns.

## Data Preprocessing 
Python ([Jupyter Notebook](./Unicorn_preprocessing.ipynb)) was used to do data preprocessing.
- The valuation and funding values in the dataset were given in strings (e.g. "$180B"). They were converted into integers.
- The industry type contains strings with same meaning but not exact match (e.g. "Artificial Intelligence" and "Artificial intelligence"). They were merged.

## Analysis
The dashboard answers the following questions:
- Which are the most valued companies? Which are the most funded companies?
- Which countries and cities have the most unicorns?
- How long did the companies take to become a unicorn? How has this changed over the years?
- Which unicorns have the highest valuation over funding?
- Which industries are the unicorns in?
