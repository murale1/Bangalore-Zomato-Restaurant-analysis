# Bangalore-Zomato-Restaurant-analysis

The basic idea of analyzing the Zomato dataset is to get a fair idea about the factors affecting the establishment
of different types of restaurant at different places in Bengaluru, aggregate rating of each restaurant, Bengaluru
being one such city has more than 12,000 restaurants with restaurants serving dishes from all over the world.
With each day new restaurants opening the industry has’nt been saturated yet and the demand is increasing
day by day. Inspite of increasing demand it however has become difficult for new restaurants to compete with
established restaurants. Most of them serving the same food. Bengaluru being an IT capital of India. Most of
the people here are dependent mainly on the restaurant food as they don’t have time to cook for themselves.
With such an overwhelming demand of restaurants it has therefore become important to study the demography
of a location. What kind of a food is more popular in a locality. Do the entire locality loves vegetarian food.
If yes then is that locality populated by a particular sect of people for eg. Jain, Marwaris, Gujaratis who are
mostly vegetarian. These kind of analysis can be done using the data, by studying the factors such as
• Location of the restaurant
• Approx Price of food
• Theme based restaurant or not
• Which locality of that city serves that cuisines with maximum number of restaurants
• The needs of people who are striving to get the best cuisine of the neighborhood
• Is a particular neighborhood famous for its own kind of food.

“Just so that you have a good meal the next time you step out”

The data is accurate to that available on the zomato website until 15 March 2019.
The data was scraped from Zomato in two phase. After going through the structure of the website I found that for each neighborhood there are 6-7 category of restaurants viz. Buffet, Cafes, Delivery, Desserts, Dine-out, Drinks & nightlife, Pubs and bars.

# Data Understanding:

I found this raw dataset in kaggle :https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants The data was in csv format. Use the urlretrieve function from the urllib.request to download CSV files from a raw URL Use a helper library, e.g., opendatasets, which contains a collection of curated datasets and provides a helper function for direct download.

# Data Preparation and Cleaning:

Load the CSV files as Pandas dataframes.
Drop unnecessary columns that are not used for further analysis.
Handled the missing values.
Remove duplicated columns.
Perform data transformation on certain columns where values are not in the correct format for analysis. Convert data types accordingly.
Rename some columns for consistent use of names in the data analysis process.

# Data Visualization:

In this data visualization analysis, we explore insights related to restaurant ratings, popular cuisines, and restaurant distribution in Bangalore. The first visualization employs a histogram to showcase the distribution of restaurant ratings, providing a comprehensive view of how ratings are distributed across various establishments. Moving on, we identify the most popular cuisines in Bangalore through visually informative charts, enabling us to understand the city's culinary preferences. Additionally, we investigate the spatial distribution of restaurants in Bangalore, presenting a visual representation of the number of restaurants in specific locations. Furthermore, we delve into the proportion of restaurants that offer delivery and table booking options, shedding light on how these services are utilized in the restaurant industry. Through these data visualizations, we aim to offer valuable insights and trends to aid in decision-making and a deeper understanding of the restaurant landscape in Bangalore."

# Answering Questions:

Which Location has More Positive rated Restaurants in Bangalore?
What is Top restaurant Chain in Bangalore?
Which Type of Food liked by most people in Bangalore?
Which location has highest number of restraurants in Bangalore?
Which location has most expensive and most affortable cost in Bangalore?



# Inferences and Conclusion
Based on the provided information, the conclusions and inferences that can be drawn are as follows:

Popular Cuisines: The most popular cuisines in Bangalore are North Indian, followed by Chinese and South Indian.

Restaurant Concentration: Koramangala 5th Block has the highest number of restaurants, making it a vibrant culinary hub in the area, offering diverse dining options.

Ratings Frequency: Restaurants in Bangalore tend to receive ratings mostly within the 3.5 to 4.5 range, indicating a generally positive dining experience.

Dining Trends: Bangaloreans have a preference for pasta, pizza, and cocktails as their favorite food choices.

Online Ordering: Bangalore restaurants are more focused on catering to online orders rather than offering extensive booking facilities for dining in.

Highly Rated Restaurants: Koramangala 7th Block stands out as an area with the largest number of highly rated restaurants in Bangalore, indicating a concentration of quality dining establishments.

Famous Restaurant Chains: Onesta, Empire Restaurant, and KFC are among the most well-known restaurant chains in Bangalore.

Upscale Dining: Sankey Road is the prominent choice for those seeking upscale and expensive dining experiences in Bangalore.

Affordable Dining: KR Puram offers a relatively lower average price range or cost of dining compared to other locations in Bangalore.
