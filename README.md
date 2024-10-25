# -csedacr-241024_female_border_deaths

# **Description**

This repository contains a dataset, code, and findings that support the preliminary analysis found in the draft "Female Deaths May Be Increasing in the Arizona Borderlands" for the Advanced Data Journalism course at CUNY Grad School of Journalism. The raw dataset "Arizona OpenGIS Initiative for Deceased Migrants" can be obtained from https://www.humaneborders.org/migrant-death-mapping. It is the result of data compiled by the nonprofit Humane Borders and the Pima County Office of the Medical Examiner from 1981 to October 2024.

# **Data**

The analysis uses two spreadsheets:
- ogis_migrant_deaths.csv: Raw data from "Arizona OpenGIS Initiative for Deceased Migrants" compiled by Humane Borders and Pima County Office of the Medical Examiner. Data ranges from 1981 to October 2024.
- female_deaths.csv: Modified data to only show the "ML Number" , "Reporting Date" and "Sex."

It also contains a line graph showing the number of remains found by year.

# **Methodology**

- The notebook female_deaths.ipynb contains a filtered version of the "Arizona OpenGIS Initiative for Deceased Migrants" to only show the "ML Number" , "Reporting Date" and "Sex”.
- Notebook also contains the your_graph later renamed as "female_graph.jpg" in the output, and an empty png of a failed code kept for transparency's sake.
- To do this you first have to upload the dataset and modify the date to only show the year
- Then filter it and create columns for "ML Number" , "Reporting Date" and "Sex" 
- Save it to a new csv file
- Then you have to graph the data in that new csv file on a line graph from 1981 to 2024 and export it as jpg

# **Output**
The new csv file female_deaths.csv and the female_graph.jpg, plus an empty png of a failed code kept for transparency's sake.

# **Running the analysis yourself**
You can run the analysis yourself with the following installed on your computer:
Python 3
Pandas library
Matplotlib library

# **Contact**

sedachab.cr@gmail.com


