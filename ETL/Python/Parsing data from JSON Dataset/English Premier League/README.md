# "English Premier League"- season match stats 2017/2018
### Extract data from "English Premier League" semi-structed (JSON) dataset, parse, transform and load into an Excel file.

Hi,Friends
I am going to show you getting data from semi-structed (JSON) dataset, parse, transform and load into an Excel file
Steps:
1. Extracting data from JSON dataset
2. Parsing and Transforming
3. Loading into an Excel file.

Used tools:
1. Jupyter Notebook
2. Pyton (Pandas Library)

JSON dataset content:
"English Premier League"-season match stats 2017/2018

![image](https://user-images.githubusercontent.com/60735401/215338209-e1eb446d-579c-473c-97a1-85ad94016394.png)

First of all
We need Jupyter notebook. We can follow the steps with different application or tools. The Jupyter notebook is one of the powerful web application for data purpose
1.	We have to import pandas.
2.	Use “read_json” function to convert JSON string to pandas object. 

![image](https://user-images.githubusercontent.com/60735401/215338281-125577ec-7b93-42b4-925e-7cf42bf0f057.png)
Pic:1

The output is not understandable because keys of JSON are defined as indexes instead of columns.
In this case, we have to use orient="index" and replace indexes to columns and columns to indexes. 
orient="index" – define indexes as columns
head(10) function – retriving 10 rows.

![image](https://user-images.githubusercontent.com/60735401/215338309-c2a2f6b5-cc51-43fb-a62d-4b56578c5d6a.png)
Pic:2