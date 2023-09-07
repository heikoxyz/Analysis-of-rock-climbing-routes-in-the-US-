**Goal of this project**

This project is aiming to get first hand experience in using more complex databasets and to apply Python-mediated data analysis.
@vnugent was so kind to extract data of rock climbing routes from various US states of the website MountainProject.

Within this projects I want to ask questions related to rock climbing in the US. 
Firstly however, this project is used to apply data wrangling and cleaning tasks to obtain a workable final output for analysis.

**The following questions and tasks about the dataset will be adressed and solved** 

**Data Wrangling**
- Does openbeta-usa-routes-aug-2020.zip contain all the data that is found across the .zip files of specific areas?
- Compare Mountain2.zip and Mountains.zip. Which dataset is more complete? Are they similar? 
- Which routes can not be found in one or the other dataset?
- Split the grade column into seperate columns for each grading system
- Split the climbing type (trad, sport, bouldering) into individual columns
- Create seperate tables for the various types of climbs 
- Proceed with the analysis of the routes of type: sport.

-> This part will be reported in code and comments in more detail (see data_preparation.ipyub).

**The following questions about the dataset will get answered**

**Data analysis**
The distribution of sport climbing routes across states by grade.
 -    Which state has the hardes sport climbing routes (most routes >=8a)?
 -    How many grades graded 9a or harder are there in the states?
 -    Which state has the most sport climbing routes?
 -    Which state has the most sport climbing routes relative to all types of climbing?
 -    What style of climbing is mostly found in each state in relative terms?
 -    Which state has the densest distribution of sport climbing routes?

-> This part of the analysis is reported in code, comments, and markdown outputs (see Analysis.ipynb)
-> To only look at the final report, the markdown output, please refer to Analysis_Results.pdf or Analysis_Results.html.

**Outlook**
This report could be further improved. For example by: 
- Making scrollable elements like long tables with filtering options
- The report mainly focuses on sport routes. One could envision a customizable report by user entry/input on a dashboard or website for example trad instead of sport, YDS grading instead of French grading,..
- Numbering of tables and a clearer structure including a table of contents.
For now no further efforts will be made to improve the report, since the main goal was not the report, but learning and applying Python, Data wrangling and visualization.
Additionally, for some ways of reporting, other tools might be more applicable like MS Office or Tableau.



