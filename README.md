# tax-service-gov-UK




## About 

spider built with [scrapy](https://scrapy.org/) to give you info about taxs using this website  [gov UK](https://www.tax.service.gov.uk/check-register-fair-rents/search-results?q=3Uz%2FLRKbuVgFceNFln3CIA%3D%3D) 

## how the spider work  work 
the spider using the post code to go to the page that contain the info


### Screenshot of this page
![output](https://github.com/abdosabry21/tax-service-gov-UK/blob/main/Screenshot%202023-12-01%20142529.png)

### 
<p> then the spider go to every result and scrape the url of it and follow the url </p>

![output](https://github.com/abdosabry21/tax-service-gov-UK/blob/main/Screenshot%202023-12-01%20142546.png)

<p>then get the info  you want form this page such as `address` and `registered fair rent`   you can scrape any info from this page using xpath i scraped the address and registered fair rent  </p>

### Screenshot of the output
![output](https://github.com/abdosabry21/tax-service-gov-UK/blob/main/Screenshot%202023-12-01%20142153.png)
