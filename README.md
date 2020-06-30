# imageScraper
This is my Project that helps to download/scrape the images from google into the local directory. Very helpful by extracting data to train the data.
### Credits
I would like to thank iNeuron for helping me learn something new about image Scraping.
### About Project
In this project the code asks for a search term from the user, after which the code replicates/automates the working of a browser in order to fetch the image urls that is not possible through the usual requests as the response is JS and not HTML. So, since the browser knows how to parse the JS methods, we use that technique to get the data through the browser.
We make use of Selenium that makes use of a web driver (GeckoDriver in my case as I use Firefox) to command the browser to fetch the required information. After fetching the URLs, the URLs are fetched and the response is stored in our directory as an image folder with another subfolder that has the name of the search term which contains the data.
#### Requirements:
- Jupyter Notebook/ any other application that can process .ipynb file.
- pip install selenium.
- install the Web Driver of the particular browser that is used.
- Put the executable file of the driver in the current working directory and run it during program execution.
#### Notes:
Brief notes are present to refer why we do not use the regular requests and fetch the data.
