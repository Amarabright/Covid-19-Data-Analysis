 
<p align="center">
  <img width="600" height="300" src="https://user-images.githubusercontent.com/83390581/179336826-30b76278-726c-43ec-8527-ada2d85a1306.jpg">
</p>


# Covid-19 Data Analysis

This project is to show the understanding and skills I have acquired in Web Scraping with Excel, Use of Power Query in Excel and also creation of Interactive Dashboard in Excel.


## Introduction
The world experienced a shift in 2020 as World Health Organisation declared a global pandemic in March 2020, caused by a Virus that originated from Wuhan, China. 

This virus is called C0VID-19 and it caused global deaths. Therefore it is of utmost interes to know the spread and death caused by this virus.

<p align="center">
  <img width="600" height="300" src="https://github.com/Amarabright/Covid-19-Data-Analysis/issues/4#issue-1306690828">
</p>
   
## Project Objectives
This is to look into the confirmed cases, recovered cases and death of people globally from Jnauary 2020 till 14th July, 2022. It is a peraonal project taht aims at udnerstanding the countries with the highest and lowest cases.
## Data Sources
This is a live Covid 19 dataset that is updated daily and in a time-series format. It is a trusted dataset uploaded by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University. it is contained in this link https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data. 

Three (3)  main datasets were of optimum importance to me. The gloabl confirmed cases, global recovered cases and global death cases.  They were scrapped using the web link (url) into Excel for cleaning and transformation.
## Data Cleaning and Transformation
Microsoft Excel 2016 is the main tool used for this project.
The Power Query Editor enables us to perform the data cleaning and transformation.

The following were done.

1. Loading o the Confirmed cases into the sheet.
2. Editing the "source" tab so that we can remove the columns and enable real time updates (dynamic)
3. The first rows were made to be headers for accurate readability.
4. I changed the data format from wide data to long dtaa by unpivoting the date columns.
5. I added new columns and named them appropriately with the first as recovered.
6. I imported the recovered  and death dataset and did the same changes on them as the Power Query saved the formatings to be applied.
7. I merged the three tables into one and then changed the format of the date column to be date format, the Recovered, Death and Confirm Columns were also changed from text format to number formats.
8. I also extracted day, month and year from the Date column into their different columns.
9. Then I began to visualise.

## Data Analysis
The Sort and Filter function was used to look throgh the dataset and remove any blank infromation.
I ended up with 257926 rows and 11 columns of clean datasets.

## Data Visualization
![COVID DASHBOARD 2](https://user-images.githubusercontent.com/83390581/179336994-bfad31d3-5344-4c70-a0c3-179da701961c.jpg)


## Findings
1.United States has the Highest prevalence of COVID-19
2.North Korea has the lowest prevalence case of COVID-19 with just 61 reported cases.
3. United States has the highest Reported Death Rate of COVID-19
4. India has the highest Reported Recovery Rate of COVID-19
5. Cummulative Monthly  confirmed cases of COVID-19 since 2020, June has the highest figures.

## Recommendation:
Get the Excel file and see the interactive dashboard that will enable you get cases for any particular day, month, year or even country.


