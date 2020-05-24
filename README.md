# Mission to Mars

![mission_to_mars](Images/mission_to_mars.png)

This web application that scrapes various websites for data about a future manned Mission to Mars and displays the information in a single HTML page. 

### Web Scraping

Initial scraping was accomplished using Jupyter Notebook, BeautifulSoup, Pandas, and Requests.

### NASA Mars News

The example program scapes data from [NASA Mars News Site](https://mars.nasa.gov/news/) and collects the latest News Title and Paragraph Text. It then assigns the text to variables that are referenced later.

```python
# Example:
news_title = "NASA's Next Mars Mission to Investigate Interior of Red Planet"

*BONUS: The news_p was something that didn't come through because of page loading. You might have to try this with Selenium.
news_p = "Preparation of NASA's next spacecraft to Mars, InSight, has ramped up this summer, on course for launch next May from Vandenberg Air Force Base in central California -- the first interplanetary launch in history from America's West Coast."
*END BONUS.

The application also scrapes the JPL web site to get image urls for the current Featured Mars Image and assigns the url string to a variable called `featured_image_url`.

### Mars Weather

Text about Mars weather is scraped from: (https://twitter.com/marswxreport?lang=en). The tweet text for the weather report is saved in a variable called `mars_weather`.

### Mars Facts

* Visit the Mars Facts webpage [here](http://space-facts.com/mars/) and use Pandas to scrape the table containing facts about the planet including Diameter, Mass, etc.

* Use Pandas to convert the data to a HTML table string.

### Mars Hemispheres

The USGS Astrogeology site (https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars) is the source for the high resolution images for each of Mar's hemispheres.

### MongoDB and Flask Application

MongoDB and Flask templating was used to create a new HTML page that displays all of the information that was scraped from the URLs above.


