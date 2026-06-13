**Web Scraping Automation Using Selenium & Python
Overview**

This project automates the extraction of structured data from web pages using Python and Selenium WebDriver. The script navigates through multiple pages, collects required information, handles pagination, and exports the extracted data into an Excel workbook.

The project includes two approaches:

Version 1: Automated pagination using predefined XPath conditions
Version 2: Manual XPath input for navigating pages dynamically

**Features:**__
Automated browser control using Selenium WebDriver
Extracts data from dynamically loaded web pages
Handles multi-page navigation through pagination
Extracts structured information from HTML elements
Stores scraped data into Excel worksheets
Uses explicit waits for reliable element loading
Automates repetitive web data collection tasks

**Technologies Used:**__
Python
Selenium
Requests
OpenPyXL
WebDriver Manager

**Libraries:**__
selenium
requests
openpyxl
webdriver-manager

**Project Structure:**__
Web-Scraping-Automation/

│── version_1.py
│── version_2.py
│── README.md
│── output.xlsx

**How It Works:**__
Launches Chrome browser using Selenium WebDriver
Opens the target website
Locates required elements using XPath and HTML classes
Extracts title-value data from web elements
Saves extracted data into an Excel workbook
Navigates through multiple pages
Continues extraction until all required pages are completed

Setup Instructions

**1. Clone Repository**__
git clone https://github.com/yourusername/repository-name.git
   
**2. Install Dependencies**__
pip install selenium requests openpyxl webdriver-manager

**3. Update Configuration**__
Before running the script, replace:
Website URL
XPath values
Excel file path
HTML class names (if different)

**Skills Demonstrated**__
Web Scraping
Browser Automation
Data Extraction
HTML Element Handling
Python Programming
Excel Automation
Selenium Automation

Author - Architha Sundarrajan
