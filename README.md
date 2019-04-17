# Mission to Mars

## Step 1 - Scraping

Complete your initial scraping using Jupyter Notebook, BeautifulSoup, Pandas, and Requests/Splinter.

* `mission_to_mars.ipynb`

### NASA Mars News

* [NASA Mars News Site](https://mars.nasa.gov/news/) 

### JPL Mars Space Images - Featured Image

* JPL Featured Space Image [here](https://www.jpl.nasa.gov/spaceimages/?search=&category=Mars).

* `featured_image_url`.

* `.jpg`.

### Mars Weather

* Mars Weather twitter account [here](https://twitter.com/marswxreport?lang=en).

* `mars_weather`.

### Mars Facts

* Mars Facts webpage [here](http://space-facts.com/mars/).

### Mars Hemispheres

* USGS Astrogeology site [here](https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars).

* `img_url` and `title`.

## Step 2 - MongoDB and Flask Application

Use MongoDB with Flask templating to create a new HTML page that displays all of the information that was scraped from the URLs above.

* `scrape_mars.py`.
* `scrape`.

* `/scrape`.
* `scrape_mars.py`.
* `scrape`.

* Create a root route `/` that will query your Mongo database and pass the mars data into an HTML template to display the data.

* `index.html`.

## Hints

* Use Splinter to navigate the sites when needed and BeautifulSoup to help find and parse out the necessary data.

* Use Pymongo for CRUD applications for your database. For this homework, you can simply overwrite the existing document each time the `/scrape` url is visited and new data is obtained.

* Use Bootstrap to structure your HTML template.

## Copyright

Trilogy Education Services © 2017. All Rights Reserved.
