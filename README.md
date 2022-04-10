# Web-Scraping - theverge
## Overview
* This project is a web scraper written in Python language.
* Its purpose is to read articles from "theverge.com" and save the data in a CSV file.

## Features
* Read the Headline, Get the link of the Article, Author Name, and the Date of each of the Articles Found on "theverge.com".
* Store these in a CSV file titled 'ddmmyyy_verge.csv', with the header 'ID, URL , Headline, Author, Date'.
* Store the same data in SQLite database.

## Requirements
* [Python](https://www.python.org/downloads/)
* [VS Code (Or Any Other IDE)](https://code.visualstudio.com/download)
* [SQLite](https://www.sqlite.org/download.html)

## Usage
* Clone the repository and open with VS Code (or any other suitable IDE).
* Install Dependencies - 

  ```pip install beautifulsoup4```
  
  ```pip install requests```
  
  ```pip install csv```
  
  ```pip install sqlite3```
  
  ```pip install pandas```
 
* Create a database named "theverge.db" using command -

  ```sqlite3 theverge.db```
  
* Run the Script with command 

  ```python script.py```
  
## Screenshots
