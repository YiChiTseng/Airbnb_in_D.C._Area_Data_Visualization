# Airbnb in D.C.Area(Data Visualization)

# Data Description

There are three main Airbnb raw datasets of "Washington, D.C., District of Columbia, United States" from Inside Airbnb.

* File Name: listings.csv.gz (We downloaded and named it "listings_DC_full.csv")<br/>
Description: Detailed Listings data for Washington, D.C.<br/>
Data Size: 9,330 rows × 106 columns


* File Name: listings.csv (We downloaded and named it "listings_DC.csv")<br/>
Description: Detailed Listings data for Washington, D.C<br/>
Data Size: 9,330 rows × 16 columns


* File Name: calendar.csv.gz<br/>
Description: Detailed Calendar Data for listings in Washington, D.C.<br/>
Data Size: 3,392,372 rows × 3 columns

The dataset listings.csv (1.6MB) contains 9329 accommodations with 16 columns which include some basic information: location information, host name, room type, the number of reviews, minimum nights limitation, etc.

The other larger dataset (31.3MB), _listings.csv.gz_, contains 9329 accommodations with 106 different kinds of detailed features, which includes not only the basic information, but other detailed features that help us analyze deeper and wider: guests reviews scores (the total number of reviews, overall review scores, scores in various aspects), description (amenities, house rules, room space), time series data (the first host date, the first reviews date, the last reviews date), performance rate (response rate, acceptance rate, is a super host or not), just to name a few.

Besides acquiring open source data sets on Inside Airbnb website. To increase the accuracy of prediction, inference, and make our findings more convincing, we also found additional resources include:

* File Name: Federal Holidays - all.csv<br/>
Description: US Federal Holidays for the period between 2017 and 2030<br/>
Data Size: 140 rows × 3 columns


* Crime Rate of Each Neighborhood from Areavibes <br/>
Description: Annual Crime Cases Number measured by every 100K people<br/> 
Website URL: https://www.areavibes.com/washington-dc/neighborhoods/

# Insights

Here is our insights:

* As what we expected, accuracy, cleanliness, checkin, communication, location and value all influence the ratings and overall scores. The increase of these factors will make the ratings and overall review scores go up. By improving the quality of serives according to these factors would level up overal review scores and ratings.

* Specifically, hosts should update the housing info and make sure descriptions and photos accuratly represent the housing stays. The price of stays should provide good values and meet expectations of guests. These two improvments would likely boost the reviews scores and rating the most. Also, cleanliness, check-in and communication experiences are important as well. Location seems to be the one factor that is hardly improve since it's physically here, but it affects the scores and ratings the least among all factors. Guests should put emphasis on improving the rest of factor performances.
