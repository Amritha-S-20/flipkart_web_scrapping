# flipkart_web_scrapping
### web scrapping of the product water purifier from flipkart
Here in this project I have scrapped about 600 water purifier details, ie, from 25 pages from flipkart. 
#### visit link:[flipkart_water_purifier](https://www.flipkart.com/water-purifiers/pr?sid=j9e%2Cabm%2Ci45&page=)

### what we do here?
Here first we identify the url pattern and the send request and after that we convert the response to a beautifulsoup object.
Then we identify the html tag corresponding to the data we want. Using that we scrap the data and append it to correspong list that we created.
After that we convert all the list to dataframe and then to csv file
### Collected details are:
* Product name
* Product price
* Product properties
* Star rating
* Total no. of ratings
* Total no. of reviews
#### Libraries used:

* Pandas
* Requests
* BeautifulSoup
* Time
* IPython.display


