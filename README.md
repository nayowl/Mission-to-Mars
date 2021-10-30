# Mission-to-Mars
## 1 Overview of the Project
Mission to mars is a web application that will scrape new data about mars  with a click of button.This web application will use NoSQL database MongodB because the data that pulled from internet comes in many different forms. For the framework it will use Flask that will allow the user to create web application using Python and customize it with HTML and CSS.

The following tasks will be performed in this analysis:
* Scrape the NASA Mars News Site and collect the latest News Image, Title and Paragraph Text
* Visit website for mars image, find and click the full image button, parse the html result using beautiful soup, create image url
* Visit website for mars facts,use panda to scrape data and convert to HTML string
* Visit website for hemisphere,create list to hold image and titles, retrieve image url and title for each hemisphere using for loop
* Use MongoDB and Flask template to create HTML page to display the result of data scraping 


## 2 Resources
Software: Python 3.7.6 , Jupyter notebook, Pandas library, Flask, MongoDB, HTML,CSS, Bootstrap 3, BeautifulSoup, Splinter, ChromeDriverManage

Website source for data scraping:
* News image and data : https://redplanetscience.com/
* Featured Image      : https://spaceimages-mars.com
* Mars Facts          : https://galaxyfacts-mars.com
* Hemisphere          : https://marshemispheres.com/

## 3 Result
Figure 1  and Figure 2 is the flask website application  that included news,news images, mars facts table and hemisphere image and title. Each time the " Scrape New Data" button is clicked, the new information will be updated both in the database and website. Figure 1 is the website application view in desktop  while Figure 2 is the website application view in the mobile device.

<p align="center">
    <img src="https://user-images.githubusercontent.com/88597187/139542385-4a443012-7ce7-403f-b870-69010320610f.png"/>
</p>

<p align="center">
  <sub> Figure 1 Website view from Desktop  </sub>
</p>

<p align="center">
    <img src="https://user-images.githubusercontent.com/88597187/139542662-9d402532-94a4-4217-8387-5ee3ccc8b80b.png"/>
  <img src="https://user-images.githubusercontent.com/88597187/139556882-de00c33c-dd8a-4c19-9cc5-cb4c713f6371.png"/>
   <img src="https://user-images.githubusercontent.com/88597187/139542677-9b510f9d-695b-4806-8ca5-98ce82fbf553.png"/>
</p>

<p align="center">
  <sub> Figure 2 Website view from mobile device  </sub>
</p>



