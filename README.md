Title
# ELECTRIC VEHICLES
## WHERE WILL YOU BEGIN
#### Collaborators:Arsam Ijaz,Hardik Gehlot, Jason Demone,Anna Puzinovici
#### Last Updated : April 23,2023
### Project Breakdown
1. Jason Demone; Back-End - Charging Station Locations, Red vs Blue
2. Anna P.; Back-End - EV Model Comparison, EV Sales Comparisons
3. Hardik Gehlot; Back-End - Government and consumer spending, Alternate Resource Comparison
4. Arsam Ijaz; Back-End - Denny's Data and Charging Locations, Front-End; Wedsite design, Main page HTML, CSS, JS

### Introduction
Electric vehicles (EVs) are gaining popularity as an eco-friendly alternative to traditional gasoline-powered vehicles. This project focuses on analyzing EV data in the USA. The study includes four datasets, each offering a unique perspective on the EV market. The first dataset examines the location of charging stations in states affiliated with different political parties (RED vs Blue). A map is provided to show the precise location of charging stations in each state. The second dataset analyzes sales of various EV models, providing a comparison of their popularity. The third dataset investigates the government and consumer share in the EV market and how it impacts demand for alternative fuel in the USA. Lastly, the fourth dataset highlights the growing popularity of EVs, as evidenced by the increased number of charging locations, which now surpasses that of Denny's restaurants.
### Objective
Given the scope of the data, this project aims to answer the following questions:
1. The affiliation of the government impacts the EV market
2. Analyze and compare different EV models in terms of sales
3. The government and customer share in the EV market and how their spending patterns affect the market
4. The growth of EVs is impacting oil consumption in the USA
5. The popularity of EVs and their future growth potential

### Guidelines
To acces the website, user is to go through the 'Main-page' folder in the repository, copy path to 'main_page.html' and populate into browser. Links to each portion of the data results are available under each respective tags.

### EV Comparison

Dropdown 1: Charging time: Here we see the charging time of many different types of EVs, and we can see that the most effective one is Porche Taycan Plus with a charging time of 960km/hr and Tesla Model S with 800km/hr
-      An interesting fact here is the Mercedes EQB can can charged from 10% to 80% battery in just 32 min
Dropdown 2: Range
-      Tesla Roadster has the highest range per charge (970 km) and Mercedes EQS which has a range of 640 km
Dropdown 3: Performance here means acceleration to 100 km/hr
Porshe Taycan Turbo can reach 100 km/hr in just 3.2 s while Ki EV6 GT takes 3.5s
Other models like the Peugeot e-Rifter Long 50 takes a total of 11.7 s and Voltzwagon ID.4 takes 10.9
We can compare this to a faster gas car such as the Lamborgini Aventador which would take 2.8s to reach 100 km/h
Dropdown 4: Affordability
We have the Nissan Leaf and Voltswagon ID.3 at around 30,000$
Porshe Taycan Plus and Audi E-tron S Sportback at around 100,000
Tesla is around 60K, I would say this car get you more bang for your buck

### Government and Consumer Spendings
- The raw data downloaded come in the form of csv files and are stored in Hardik folder. The below steps area the approach to do the analysis.
1. The Data wrangling and cleaning was done by Python and Pandas and stored to Hardik_Data folder.
2. The Data merging and type change was done by the pandas using Jupyter Notebook.
3. The merged Data was then stored in pgAdmin SQL Database by establishment of a connection between python and pgAdmin.
4. Using python, a flask app named app.py was created to develop a flask API.
5. HTML file was created to form DOM for web development.
6. Javascript named hardik.js is importing data from api and then plotting interactive visualization on web.
a. Government Goverment spending share in the EV market.
![Goverment spending](https://user-images.githubusercontent.com/120690578/233892121-222997bc-4e6a-4075-8653-9b7e0c0e57eb.png)
* The line plot visuals chart the Government Share in Billion USD is decreasing steadly from 2015 to 2023.The red line represents Government Share.
* The graph shows government needed to promote ev market in early days due to less successs and popularity of electric vehicles among common people.
* The share is getting down, which shows less push is need to promote the ev market.
* The graph throw light on more private companies are increasing their ev production share in the market.
b.
![Consumer spending ](https://user-images.githubusercontent.com/120690578/233892996-a5302d8c-49eb-4987-a462-18143b7b9c64.png)
* The line plot visuals chart the Consumer Share in Billion USD is increasing steadly from 2015 to 2023.The green line represents Consumer Share.
* The graph shows  Consumer (common people ) is taking more interest in electric vehicles.
* More spending shows the morea delevoped technologies which are reliable for different activites like long distant travelling, heavy duty truck etc
* The share is getting up the future growth is exponential and promising.
c.
![barrels consumption in USA](https://user-images.githubusercontent.com/120690578/233893794-d7f7e550-3be1-4030-8b10-bfc887ef52fa.png)
* The bar graph shows the barrel consumption per day in USA.
* The growth in EV market and fuel prices affecting oil consumption in us negatively.
* The less consumption helping the environment and dependency of a country on fossil fuel.

### Denny's
A decision to start proceeding towards to EV market requires users to understand how easy chargin time are going to be. Where we have seen large chargin times in EV Comparison, we understand that users need to spend the quality time productively instead of sitting in their car waiting for charge to complete. 

We've design a map that, therefore, shows the locations of each chargin station, along with the location of each Denny's Restaurant. Understanding that this prototype website is targetting Americans, and is showcasing only a validation of a working code, we have have chosen Denny's as a sample restaurant.

The data, which is available as the SQL database, needs a flask ORM to have access. For ease of data access, the data has been converted to an array in a JS file.
