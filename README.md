# Data-Analyst-Porfolio
Hello, thank you for stopping by!
My name is Abdirahman (Abdi) Yusuf. I'm a data analyst based in the Minneapolis-Saint Paul area. 

Here is one of the projects I have done. Stay tuned for more!

## Used Vehicles Under $6,000 within 40 miles of Minneapolis

### Repository: 
The visualizations can be found in [here](https://public.tableau.com/app/profile/abdirahman.yusuf1824/viz/used_vehicles_facebook_marketplace/UsedVehiclesUnder6000onFacebookMarketplace).
The Tableau Story describes the business task, visualizations of key metrics, and final recommendations for the stakeholder.

### Inspiration and Goal for the Project: 
In June 2024, I was looking for a used vehicle and attending Hack the Gap’s data analytics boot camp. I used the capstone project to make a more informed decision while practicing  the skills gained in the data analytics boot camp.  The business task is to determine the best-used vehicle (small sedans of the following Makes: Toyota, Honda, Nissan, and Ford) to purchase for under $6,000 within 40 miles of Minneapolis, available on Facebook Marketplace in June of 2024. The stakeholder is myself! 

### Description of the Project
This project aims to answer two questions.   

**Question 1:**  
Under the following parameters   
- Budget - $4,000 to $6,000   
- Distance - within a 40-mile radius   
- Make - Toyota, Honda, Nissan, Ford   
- Year Range - 2010 to 2019    
What makes, years and models have the highest inventory, therefore should the target for purchasing?
      
**Question 2:**   
Based on the insights from this analysis, what specific year and model should be targeted?         

### Skills and Technologies Used In This Project
#### Data collection: 
I scraped Facebook marketplace listings using Python, BeautifulSoup, Splinter, and Pandas. 
#### Cleaning and Transforming:
The Python scraper program downloaded a CSV file with 1,216 entries. Since the entries are not too large, I used Excel sheets to clean the data. 
To find and remove empty cells, I used conditional formatting to highlight and delete empty cells. 
To remove duplicates, I used the Data Cleanup tool. 
To trim white space, I used the trim() function
I ensured that all columns are properly formatted. For example: the mileage should be numbers, the price is currency($), etc
There were a few makes other than Toyota, Honda, Nissan, and Ford. Therefore, I had to use the Filter tool and delete these unwanted entries. 
Total number of rows before cleaning was 1,216 
Total number of rows after cleaning was 652. 

### Results


