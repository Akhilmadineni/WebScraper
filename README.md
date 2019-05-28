# Web Scrapping Wikipedia Tables using python

**Web Scraping** (also termed Screen **Scraping**, **Web** Data Extraction, **Web** Harvesting etc.) is a technique employed to extract large amounts of data from websites whereby the data is extracted and saved to a local file in your computer or to a database in table (spreadsheet) format.

### Goal


Write a scraper in either python or NodeJS to collect data from Wikipedia about the top cities in the United States. The fields you collect, as well as the volume of data is up to you, but ideally you add additional data beyond the initial table, such as data found on the individual city pages, or other sources of your choice. The final format should be a CSV file that is ready to be uploaded to a BigQuery table. Please read Bigquery’s Manual to prepare your CSV in the right format. Intermediary steps, environments or processes necessary to run the scraper should be documented in code as well as a Readme.md and hosted on github in a repo devoted to this assignment.

### Instructions

Download .ipynb file and upload it to Google Collab and run it. Google Collab Tutorial(Link: https://towardsdatascience.com/getting-started-with-google-colab-f2fff97f594c )

#### Prerequisites

In this project, we are using Jupyter Notebook with python3 but any .ipynb editors(like google Collab) with python 3 works. 

### Solution

I have provided two solutions in this repo.

The first one is using python's beautiful soup module which is for data extraction. Data manipulation and cleaning is done using Python's Pandas library.

In the second solution will extract data from web using "read_html" function from python's pandas module. Using the same pandas library, data manipulation and cleaning were done.
