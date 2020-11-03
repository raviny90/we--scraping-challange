# web-scraping-challange

## Mission to Mars

A web application that scrapes various websites for data related to the Mission to Mars and displays the information in a single HTML page.

### Folders:
mission_to_mars.ipynb ---> has the Jupyter Notebook of original scrape code for entire homework.

scrape_mars.py ---> Python File that contains two functions; init_browser() (to initiate browser via chromedriver) and scrape() (to perform scrape of all pages taken from original Jupyter Notebook).

app.py ---> Python/Flask App that utilizes scrape() function from scrape_mars.py to update mars_app DB collection in MongoDB and load as webpage from index.html.

templates(Folder) ---> HTML webpage used for Mission to Mars that displays the information from our web application scrape.

2 total PNG images of the Mission to Mars web HTML web page app.

### How to:
To run application, please navigate to directory via console. Run mars_app.py as Python file.
