# Wrangle-and-Analyze-Data-WeRateDogs-Project
## Wrangling, Analysis and Visualization of Data ---- Udacity Data Analyst Nano Degree Project

### Project Overview
Introduction
This project was part of the Udacity Data Analyst Nanodegree program's data wrangling segment and is mostly focused on wrangling data from the WeRateDogs Twitter account using Python, as documented in the Jupyter Notebook. This Twitter account ranks pet dogs while providing hilarious remarks about them. The rating denominator is often ten, although the numerators are typically more than ten. Why? Because "they're good dogs, Brent." WeRateDogs has over 6 million followers and has received international media coverage.
WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017.
What kind of software do I need?
On your PC, you must be able to work in a Jupyter notebook. The following libraries (packages) must be installed. These packages may be installed using conda or pip. Package installation instructions may be found in the Udacity Anaconda tutorial from earlier in the Nanodegree program.
•	pandas
•	NumPy
•	requests
•	tweepy
•	json

### Project Specifications
### Code Functionality and Readability
All of the project's code is included in wrangle_act.ipynb, a Jupyter Notebook that runs without problems. The logical framework of the Jupyter Notebook is obvious and simple to understand. The code makes good use of comments and includes Jupyter Notebook Markdown cells. The steps of the data wrangling process (i.e. gather, assess, and clean) are clearly identified with comments or Markdown cells, as well. The notebook is appropriately formatted. This makes the work easy to follow.

### Gathering Data
Data is gathered:
•	From at least the three (3) different sources on the Project Details page.
•	In at least the three (3) different file formats on the Project Details page.
Each piece of data is successfully gathered and separated into pandas dataframes. The data files are in 3 different file formats.

### Assessing Data
Two types of assessment are used:
•	Visual assessment: each piece of gathered data is displayed in the Jupyter Notebook for visual assessment purposes. Once displayed, data can additionally be assessed in an external application (e.g. Excel, text editor).
•	Programmatic assessment: pandas' functions and/or methods are used to assess the data.
I have effectively performed visual and programmatic assessments. Note that this is one of the most important parts of the data wrangling step. This gives you some insight on the data you are about to work on.

Tip
Some more functions that could be used for assessment are:
•	unique(): The unique() function is used to get unique values of Series object.
•	isna(): This indicates whether values are missing
•	info(): This method prints information about a DataFrame including the index dtype and columns, non-null values and memory usage.
•	columns: This produces a list of all the columns in the dataframe
There are many more. Please feel free to explore when you can.
At least eight (8) data quality issues and two (2) tidiness issues are detected, and include the issues to clean to satisfy the Project Motivation. Each issue is documented in one to a few sentences each.
•	A very good job is done by limiting the numerators to max 20. Everything is very well explained and detailed. 

### Cleaning Data
•	The define, code, and test steps of the cleaning process are clearly documented.
•	The different steps in cleaning the project have been clearly defined.
•	Copies of the original pieces of data are made prior to cleaning.
•	All issues identified in the assess phase are successfully cleaned (as possible) using Python and pandas, and include the cleaning tasks required to satisfy the Project Motivation.
•	A tidy master dataset (or datasets, as appropriate) with all pieces of gathered data is created.
•	Copies of the original data frames have been made and all issues identified in the assess phase were successfully cleaned.
•	I perform a test before cleaning in order to show that the results are different after cleaning.

### Storing and Acting on Wrangled Data
•	The cleaned dataset has been combined to a master dataset (twitter_archive_master.csv) and successfully saved.
•	I was able to produce at least 3 insights on the data.
•	I produced at least one clear visualization.
•	I have properly assessed and cleaned the issues that I visualized.

### Report
There are two reports:
•	The wrangling efforts are summarized in the wrangle report.pdf document.
•	In act report.pdf, the student communicates three (3) or more insights, including visualization.

### Project Files
The following files (with identical filenames) are included:
•	wrangle_act.ipynb
•	wrangle_report.html
•	act_report.html
All dataset files are included, including the stored master dataset(s), with filenames and extensions as specified on the Project Submission page.
All the necessary files are present in the submission.

