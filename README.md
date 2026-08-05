# cs50-notes**
**Introduction**

A data analysis project designed with the aim of breaking down the sales information of a seller to individual and business customers in various states in the USA. It involves several graphs done using matplotlib.pyplot; whose goal is to provide a clearer picture of sales performance and fragmentation. In addition it also features interactive graphs that provide the user with the ability to take a more focused look into the data and analyze the performance of different states, and sub categories in every state.  

**Data source**
https://www.kaggle.com/datasets/bravehart101/sample-supermarket-dataset/data?utm_source=chatgpt.com

**Dependencies**
numpy
pandas
plotly
dash 
matplotlib.pyplot

**IDE** 
Jupyterlab

**Data assessment**

  **Integrity**

The data posed no challenge and its cleaning was very straightforward as it had no fault. Checks were conducted for mismatching values, missing data and null variables but none were found, as a result it could be used without any further checks or cleaning. 

  **Procedures**

Checks were done for rows with missing values and a number count was conducted to find and sum them up, which found none. In addition a further routine check was done to find any mismatching and duplicate values in multiple cells which also found nothing. Through these checks alone it was ascertained that the data was clean and suitable to use for analysis. 

**Purpose**

Provide information about sales allowing for better decision making in regards to product investment, areas of expansion, marketing and advertising focus and areas with growth potential. The graphs presented here in allow the user to see the distribution of their sales in the country as well as which goods are bought by what states in the country, which will be useful during times of restocking and chain expansion ensuring good openings and performance of new stores. In addition it highlights areas of underperformance whether due to poor product choices or lack of consumer demand which helps them cut down on spending on less desired goods. Overall the analysis is useful when deciding direction, analyzing performance and in assessing where they are in relation to previously agreed upon long-term goals

**Key Takeaways**

The first takeaway from this is that most of the sales and profit is generated from the first 5 states and then it drastically decreases after that to a point where it might not be considered significant. This is a sign of either an underdeveloped market that can be tapped into or low consumer demand. Given the history of the United States and that most of its population lies in the most revenue and profit generating states these readings make sense, but the most concerning measure is the almost none existent sales and profit coming from Idaho, Southern Dakota, and New Hampshire who all by population readings who all possess a population of more that 1 million people. 

An interesting take away is that California is the largest consumer of all three categories of technology, office supplies and furniture, and its total consumption dwarfs all other states by almost double. Interestingly its largest purchase lies in office supplies and in that it mainly purchases binders and paper which infers that most of their purchases are made by offices, schools or company's. This informs that the largest market in California is the one made to provide for the needs of common office supplies. 
The most shocking revelation is the size of the furniture sales in the California. It has the smallest amount of sales made to the point where it occupies less than 10% of all total sales and even an lower profit proportion. 

The popularity of products and sub categories is also worth analyzing as the most popular goods regardless of state are always appliances and paper for office supplies, and copiers and phones for technology. These are products whose profit margins and sales are the highest in proportion for every state, but in contrast furniture whether in chairs, furnishings is a hit and miss sector as in some states they are all making loses in terms of profit and in others they just seem to be breaking even. The furniture industry seems to be struggling in the USA, whether due to competition or a lack of demand because of the reduction at the rate of construction because of falling prices in real estate it is not a good industry to develop towards at this time.

**Challenges**
The project was fairly straightforward and posed little challenge initially, and it was only during the use and implementation of Dash was it challenging. This because of my own unfamiliarity with the module despite having read the documentation and using AI to constantly debug code and mistakes. In addition the use of 2 varying inputs also proved to be laborious as the result you see was not what was desired. The vision of this project would be one that would allow the user to have great freedom and autonomy in the choice of inputs for every graph and not just one drop down menu for every graph that would then change the variables for every single graph at once. I wanted to avoid this as it would prevent a hindrance to data analysis as the user would not be able to compare the sales or profits of different categories and sub-categories side to side, which put more of the burden on the user to recall the information. 
 

