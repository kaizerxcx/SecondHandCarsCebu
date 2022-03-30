# Predicting the Price of Used Cars in Cebu using K-Nearest Neighbor and Multiple Regression Algorithm

*•Arnado, Russ Azzi • Degamo, Ma. Lezly Grace • Mayormita, Riza Marie • Perez, Rodel • Tabañag, John Kaizer*

### Overview of the Study
***

Cebu with it's population of 7,396,898, is one of the richest province in the Philippines with its annual GDP of 1,156,592 pesos. With its booming population and busy people, the demand for cars is increasing rapidly. According to Land Transportation Office Region 7, the number of newly registered vehicles in Cebu will increase year and major cities in Cebu alone may have 800,000 registered vehicles by the end of 2019.

The purchasing behavior of customers in the secondhand car market has been affected by the growing popularity of online classified advertisements and auto portals in the Philippines. The digital era’s technological advancements gave birth to various online platforms in which potential customers can explore in their journey of finding a car that would best suit their preferences. Various multi-brand dealers are strategically partnering with online classified advertisements and auto portals to make the car purchasing journey of potential buyers to be more convenient, accessible, and transparent. 

Due to the Tax Reform for Acceleration and Inclusion (TRAIN) Act in the Philippines, new vehicles have become more expensive which results to individuals resorting to certified and non-certified secondhand vehicles. The increase in demand on public transport and ride-sharing services to relieve traffic congestions will also expand the sales of used cars in the Philippines.

Buying secondhand cars may have its advantages (e.g., cheaper) but it also has its risks such determining the reliability of the seller and whether if a used car is overpriced or not. 

To help alleviate the worries of potential used car buyers in their purchasing journey, we will now try to develop a model that would predict the price of secondhand cars and identify which specific features/variables greatly affect it.

**Buying used cars has many advantages:**

- More savings
- Cheaper insurance cost
- Slower depreciation
- Extended warranty
- Good for the environment

**But there are also risks:**

- Unknown reliability or treatment
- More frequent maintenance
- Hard to find an exact match of what you want
- Untouched warranty
- Lemon Car / Overpriced Car

### Variables Used
***
- **ID** - Default primary key of the car records.
- **Title** - The title or the name of cars displayed in the scraped website.
- **Price** - The second hand price of the car.
- **Brand** - The brand name of the car.
- **Model** - The model name of the car.
- **Year of Manufacture** - Car year of manufactured.
- **Used** - A binary attribute that indicates wheather the item is second hand or not.
- **Transmission** - Can be manual or automatic transmission.
- **Color Family** - Car colors classified into color family.
- **Mileage (in km)** - the total number of miles that the vehicle have travelled at the time it was purchased.
- **Body Type** - Car style or type.
- **Version** - Car's version number.
- **Description** - Car's description in the website listing.
- **Poster** -The one who post/sell the car in the website.
- **Poster Type** - The type of entity/seller who post the item in the website.
- **Fuel Type** - Car's fuel type
- **Location.2** - Poster/Seller's location
- **Date Posted** - Date of when the item is posted
- **name** - Name of the car
- **retail** - Original Retail price of the car in the market.
- **Post Age** - The age from when it is posted by the poster/seller in 
