# Mission-to-Mars
 
# Overview 
The purpose of this project is to scrape images, tables, data and text from four different sources:
 - https://data-class-mars.s3.amazonaws.com/Mars/index.html
 - https://data-class-jpl-space.s3.amazonaws.com/JPL_Space/index.html
 - https://data-class-mars-facts.s3.amazonaws.com/Mars_Facts/index.html
 - https://marshemispheres.com/

After collecting the data, it is formatted and stored in a mongo database.  A flask application retireves the data from mongo and displays it to the user with help from bootstrap 3 CSS.
