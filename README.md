# Web-Scraper-Assignment

My task was to extract specific data from the "task 1 - Kempinski Hotel..."-HTML file.  
Here is what I did: 

This scraper uses Python3 and Selenium. The input is HTML and the output a JSON string.

Selenium for Python can be downloaded via pip, this is the documentation:
https://selenium-python.readthedocs.io/getting-started.html

Besides Python3 and the Selenium framework it needs Google Chrome to run and the chromedriver.exe more specifically. 
You can download the chromedriver for your system on this page:
https://chromedriver.chromium.org/downloads

After downloading the chromedriver.exe, all you need to do is to store it in a folder of your choice and copy the path.

If you open the HotelScraper.py this is the very top part:

![HotelScraper py1](https://user-images.githubusercontent.com/91540358/211194679-a092a36c-2f33-49fd-bc5c-50cd591a98d1.png)

The only import parts are PATH_HTML and PATH_CHROME_DRIVER. 
PATH_HTML is where the HTML to scrape can be found and PATH_CHROME_DRIVER is where you enter the
path to your chromedriver.exe (which you copied earlier). 

HEADLESS_BROWSER is activated by default, it deactivates the browser during the scraping. It can be activated by changing it to FALSE.
JSON_OUTPUT_NAME is just the name of the output JSON - if not changed it will create a JSON string called 'results.json'.

To start you just need to run the file. The output will be stored in the same directory.

