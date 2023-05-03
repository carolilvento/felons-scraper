# Career Felons Scraper

This is a Python script that scrapes a the Florida Department of Law Enforcement [website](http://www.fdle.state.fl.us/coflyer/home.asp) to collect information about career felons in the state. The information is extracted using the BeautifulSoup library to parse the HTML content of the website. The collected data is saved in a CSV file named "felons.csv".

## Purpose
The purpose of this scraper is to collect data on felons in the state of Florida. This data was then used in a project matching career felons to sex offenders.

## Functionality
The script makes a POST request to the Florida Department of Law Enforcement's website and retrieves the HTML content using the requests library. The BeautifulSoup library is used to parse the HTML content and extract the required information. The nameparser library is used to parse the names of felons, and the dateutil library is used to parse the date of birth. The extracted information is saved in a CSV file using the csv library.

## Output
The output of this script is a CSV file named "felons.csv" that contains the following information:

* Last Name
* First Name
* Middle Name
* URL of the felon's detail page
* Date of Birth

The CSV file is saved in the same directory as the script. Each row of the CSV file represents information about one felon.




