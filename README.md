# Title: Data Gathering for Movie Reviews

## Description:

This project walks through four major sources of gathering data for analysis by a data analyst.
I have covered the following use cases:
1. Downloading manually: Already gathered data in a CSV file sent to the analyst
2. Web scraping
3. Downloading Programmatically
4. Downloading from Databases

The goal is to cover the aforementioned data gathering use cases and create a master dataset for further analysis. However, the analysis or visualisations will not be covered in this project. 

Libraries employed in this project include: 

- pandas - to handle dataframes
- glob - for pattern matching (specifically to identify select file types in a folder)
- beautiful soup - for webscraping
- requests - to programmatically download files using their urls
- os - to create new file directories
- wptools - an access library to use the `mediawiki` API for wikipedia
- sqlalchemy - to create a sqlite relational database
- io - to handle image files downloaded
- PIL - to handle image files downloaded

### Reference 

This was a capstone projects in the Udacity Data Analyst nanodegree program.
