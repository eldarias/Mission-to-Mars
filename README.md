# Mission-to-Mars
Module 10: Mission to Mars - Web Scraping with HTML/CSS

## Overview of the analysis
The purpose of the challenge was to modify the existing web app to include Mars' all four Hemisphere images and titles by scraphing URL: https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars.  **BeautifulSoup** and **Splinter** were used to scrape for full-resolution images of Mars' hemisphere and the associated titles.  Finally, the scraped data was stored on a **Mongo** database and a **Flask** web app was used to display the results.


## Results
Below are example images of the Flask web app display using different views and making minor changes to the CSS styles:

- Regular Display 1
    - <image src="./Results/Image1.PNG" width="200" height="400"><b></b>
- Regular Display 2
    - <image src="./Results/Image4.PNG" width="200" height="400"><b></b>
- Display with basic CSS style changes
    - <image src="./Results/Image2.PNG" width="200" height="350"><b></b>
- Display using iPhone 12 Pro dimensions
    - <image src="./Results/Image3.PNG" width="200" height="250"><b></b>


## Summary
In summary, all four Hemisphere images and titles for Mars were successfully scrapped, added to Mongo database and displayed via Flask web app.