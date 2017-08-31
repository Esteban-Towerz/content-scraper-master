# Content Scraper

![node](https://user-images.githubusercontent.com/25851867/29894011-a6485952-8d99-11e7-850b-fe491b9215bb.png)

I've Build a Content Scraper :squirrel: a Node.js command line application that goes to an ecommerce site[http://www.shirts4mike.com/](http://www.shirts4mike.com/) to gets the latest price, title, url, and image url from the product page and save this information into a CSV file.

![jabberwocky](https://user-images.githubusercontent.com/25851867/29900810-a96f8eaa-8db9-11e7-9544-bda7241216ed.png)

## Getting Started
in your Console:
```
$ npm install content-scraper
```

go to a content-scraper-master folder and type
```
npm start
```
Open /data folder to see generated csv file

## Project Requirements
* [x] Create a scraper.js file that will contains  your command line application. your project should also include a package.json file that includes your project’s dependencies. the `npm install` commad should install your dependencies.
* [x] program your scraper to check for a folder called ‘data’. if the folder doesn’t exist, the scraper should create one. If the folder does exist, the scraper should do nothing.
* [x] Choose and use two third-party npm packages, One package should be used to scrape content from the site. The other package should create the CSV file. Be sure to research the best package to use (see the project resources for a link to the video about how to choose a good npm package)
#### Both packages should meet the following requirements:
  * At least 1,000 downloads
  * Has been updated in the last six months

* [x] Progam your scraper so that it visits the website http://shirts4mike.com and use http://shirts4mike.com/shirts.php as single entry point to scrap information for 8 tee-shirts from the site, without using any hard-code url likes shirts4mike.com/shirts.php?id=101.If you’re unsure of how to get started, try googling ‘node scraper’ to get a feel for what a scraper is and what it does.

#### Scraping and Saving Data:
* [x] The scraper should get the price, title, url and image url from the product page and save this information into a CSV file.
* [x] The information should be stored in an CSV file that is named for the date it was created, e.g. 2017-08-30.csv
* [x] Assume that the column headers in the CSV need to be a certain order to be correctly entered into a database, they should be in this order: Title, Price, ImageURL, URL, and Time.
* [x] The CSV file should be saved inside the ‘data’ folder.

#### If your program is run twice, it should overwrite the data in the CSV file with the updated information

#### If http://shirts4mike.com is down, an error message describing the issue should appear in the console
* [x] the error should be human-friendly, such as “There’s been a 404 error. Cannot connect to the to http://shirts4mike.com
* [x] to test and make sure the error message displays as expected, you can disable the wifi on your computer or device
