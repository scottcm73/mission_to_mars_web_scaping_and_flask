# Mission to Mars

![mission_to_mars](Images/mission_to_mars.png)

This web application that scrapes various websites for data about a future manned Mission to Mars and displays the information in a single HTML page. 

### Web Scraping

Initial scraping was accomplished using Jupyter Notebook, BeautifulSoup, Pandas, and Requests.

### NASA Mars News

The example program scapes data from [NASA Mars News Site](https://mars.nasa.gov/news/) and collects the latest News Title and Paragraph Text. It then assigns the text to variables that are referenced later.

The application also scrapes the JPL web site to get image urls for the current Featured Mars Image and assigns the url string to a variable called `featured_image_url`.

### Mars Weather

Text about Mars weather is scraped from: (https://twitter.com/marswxreport?lang=en). The tweet text for the weather report is saved in a variable called `mars_weather`.

### Mars Facts

Mars Facts webpage (http://space-facts.com/mars/) is another source, and Pandas is used to scrape the table containing facts about the planet including Diameter, Mass, etc.

### Mars Hemispheres

The USGS Astrogeology site (https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars) is the source for the high resolution images for each of Mar's hemispheres.

### MongoDB and Flask Application

MongoDB and Flask templating was used to create a new HTML page that displays all of the information that was scraped from the URLs above.


