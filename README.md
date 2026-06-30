**Web Scraping Automation Using Selenium & Python
Overview**

This project automates the extraction of structured data from web pages using Python and Selenium WebDriver. The script navigates through multiple pages, collects required information, handles pagination, and exports the extracted data into an Excel workbook.

The project includes two approaches:

Version 1: Automated pagination using predefined XPath conditions

Version 2: Manual XPath input for navigating pages dynamically

**Features:**
1. Automated browser control using Selenium WebDriver
2. Extracts data from dynamically loaded web pages
3. Handles multi-page navigation through pagination
4. Extracts structured information from HTML elements
5. Stores scraped data into Excel worksheets
6. Uses explicit waits for reliable element loading
7. Automates repetitive web data collection tasks

**Technologies Used:**
1. Python
2. Selenium
3. Requests
4. OpenPyXL
5. WebDriver Manager

**Libraries:**
1. selenium
2. requests
3. openpyxl
4. webdriver-manager

**Project Structure:**

**How It Works:**
1. Launches Chrome browser using Selenium WebDriver
2. Opens the target website
3. Locates required elements using XPath and HTML classes
4. Extracts title-value data from web elements
5. Saves extracted data into an Excel workbook
6. Navigates through multiple pages
7. Continues extraction until all required pages are completed

Setup Instructions-

**1. Clone Repository**
git clone https://github.com/yourusername/repository-name.git
   
**2. Install Dependencies**
pip install selenium requests openpyxl webdriver-manager

**3. Update Configuration**
Before running the script, replace:
Website URL
XPath values
Excel file path
HTML class names (if different)

**Skills Demonstrated**
1. Web Scraping
2. Browser Automation
3. Data Extraction
4. HTML Element Handling
5. Python Programming
6. Excel Automation
7. Selenium Automation

Author - Architha Sundarrajan
