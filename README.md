<p align="center">
<img src="images\Coffee_image.png">

# Coffee_Analysis
An analysis and visualization of worldwide coffee production and consumption.
## General Information
Though I have been involved in may analysis projects, this project is my first "stand alone" analysis. No tutorials, no solution code, just using what I have been learning through various classes in Data Analysis and Visualization.

The project involves:

- Preprocessing the data
- DataFrame creation for analysis
- Data visualization

I hope to answer:
- who are the top 5 countries for producction, importing, and consuming coffee?
- what has the growth been for these countries?
- which country has seen the largest growth?
- who are the top 5 coffee importers?
- who are the top 5 exporters?

I am sure there will be additional questions that will arise during the anaylsis and visualizations.

## Data
### Data information

The data covers the production, consumption, import, export, and re-export of coffee from 1990 to 2020 in ICO countries.

Data was downloaded from the International Coffee Organization (ICO) website
[ICO Data](https://www.ico.org/new_historical.asp)

Permission is given on the historical data page "The selected data may be downloaded in PDF format (Acrobat Reader) or in a Excel file for analysis, provided the International Coffee Organization is clearly acknowledged as the source of data"

## Technology Used

### Computing Platform
- Jupyter notebook

### Packages used
- Pandas
- Numpy
- Matplotlib
- Seaborn

## Status of project
- Uploading data &#9745;
- Preprocessing data &#9745;
- Creating cleaned csv files &#9745;
- Data analysis & visualization &#9745;
- Final reporting &#9745;

## Preprocessing

Here are some of the code line I used to preprocess the data. All files were .xlsx sheets imported. After getting the data where I wanted it,  I save all as .csv files to read in for  the analysis & visualizations.

<img src="images\import.png">
<img src="images\clean-preprocess.png">
<img src="images\export-csv.png">


## Reporting

Upon anaylsis of the data, I was a little surprised at who was on top. I did not know that Brazil had such a lead in all areas regarding coffee. 

<img src="images\top5_producers.png">

Number 2 was the biggest surprise for me. If not #1, I expected to see Columbia at least in the #2 spot. Well, it was. However Viet Nam surpassed Columbias production and has been continually growing. It has had the largest growth in production.

<img src="images\top5_over_time.png">

The top 5 importers, seen below, are from all across the globe. Seeing the number of Starbucks, Dunkin Donuts, and various other coffee shops throughout every state I have been in, I knew we would have to be near the top of this list. 

<img src="images\top5_imports.png">

The top 4 of the top 5 are the same as the top 5 Producers. India out paced Ethiopia for Exporting though.

<img src="images\top5_export.png">

Seeing the difference between Brazil's Production and Exporting made me wonder where the rest of the coffe went. Well, the answwer is in consumption! Brazil leads the way by a large margin!

<img src="images\top5_consumption.png">

Overall this was an eye opening analysis. I did learn a lot about who produced, exported, imported, and consumed the most coffee. There were only a coulple of things about the data set that were a little disappointing. It may be due to affiliation, but knowing that South Korea is a large importer of coffee, I would have expected to see some data in the set.The United States ReExports a lot of coffee there, as well. Another thing I would have liked was a breakdown of the European Union to see more detail. I will look for further data to see if I can find these included. A future endeavor with coffee data, if I can find a dataset with more depth, will be in the form of a dashboard.
