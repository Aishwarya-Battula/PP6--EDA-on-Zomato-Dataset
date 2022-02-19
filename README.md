# PP6--EDA-on-Zomato-Dataset

The objective of the project is to perform analysis on the Zomato dataset and understand few items such as:
1)Find rows with missing values
2)Which country has the most no. of Zomato users
3)Which cities have the maximum no. of Zomato users
4)Identify how many users have provided ratings
5)Categorize data based on rating
6)Identify currencies of the countries

Data
Fetching the data:
• Data has been collected from the Zomato API in the form of .json files(raw data) using the url=https://developers.zomato.com/api/v2.1/search?entity_id=1&entity_type=city&start=1&count=20
• Raw data can be seen here

Data Collection:
Data collected can be seen as a raw .json file here

Data Storage:
The collected data has been stored in the Comma Separated Value file Zomato.csv. Each restaurant in the dataset is uniquely identified by its Restaurant Id. Every Restaurant contains the following variables:

• Restaurant Id: Unique id of every restaurant across various cities of the world
• Restaurant Name: Name of the restaurant
• Country Code: Country in which restaurant is located
• City: City in which restaurant is located
• Address: Address of the restaurant
• Locality: Location in the city
• Locality Verbose: Detailed description of the locality
• Longitude: Longitude coordinate of the restaurant's location
• Latitude: Latitude coordinate of the restaurant's location
• Cuisines: Cuisines offered by the restaurant
• Average Cost for two: Cost for two people in different currencies 👫
• Currency: Currency of the country
• Has Table booking: yes/no
• Has Online delivery: yes/ no
• Is delivering: yes/ no
• Switch to order menu: yes/no
• Price range: range of price of food
• Aggregate Rating: Average rating out of 5
• Rating color: depending upon the average rating color
• Rating text: text on the basis of rating of rating
• Votes: Number of ratings casted by people

