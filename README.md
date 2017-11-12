Hello, welcome to City Host!

This file attempts to allow the users to have a better understanding about the general functions of the web app.

Project Name: City Host

Project Purpose: The website helps people who might be interested in becoming Airbnb hosts to better understand the market, and what they can do to utilize/optimize their properties.

Website Functions: The website mainly has three functions.

Function 1) The users can scroll down the bar to find "INTERESTING FACTS ABOUT BEING A HOST", and there are three sections ("More Beds More Money", "People Love Kitchens", and "Secrets to Become Popular"). The users can click on the icons to go to the according sections. For example, let's go to the "More Beds More Money" section. One can clearly see from the graph that, holding every other variables constant, the more beds there are in the Aibnb, the higher price the host charges (This is also why I make sure the users to include the number of beds they have throughout the project). The users can find three interesting metrics/patterns about being an Airbnb host!

How I accomplished this: I used Jupyter Notebook (a text editing environment) and Python3 to import all the data from listing.csv (given). Then I parsed the data to show the correlations I found to be interesting. For example, for the "Secrets to Become Popular" section, I found a negative correlation between the number of reviews and the unit price of the Airbnb (this is just price/beds based on the fact more beds more money). I found the correlation by finding the standard unit and standard deviation and then used them to find the regression line. 

Code: The code for Function1 can be found in graphs. If one clicks on graphs, and one can see four different folders. Each of those folders include the code of how I generated the graphs and found the patterns (the HTML file is probably the easiest for users to read).


Function 2) At the top of the website, the users can type in their Geo-locations (latitude and longitude) and number of beds in the properties to figure out the estimated weekly income in that area. This function is both useful to Airbnb Hosts and to guests. They can easily figure out how much money they can make per week.

How I accomplished this: For this, I generated a function to do the estimation for me. I was originally thinking about to parse through all the data, and find the closest location and use that as the estimation, but I think that might not be accurate enough, so I decided to generate a fuction. I parsed all the data using Python3 and Jupyternote book to find a correlation between the Geo-location and the price (I also asked the users to input the number of beds, because that would affect the price).

Code: The code for this can be found in folder location_price. If one opens the location_price.html, one can easily see the code of the correlation and find the graph which I used to figure out the formula. After I get a graph, I used the formula graph conversion website to convert the correlation into a formula. The details of the function can be seen at the bottom of the index.html file.


Function 3) Another function is that the users can type in their Geo-locations and the number of beds in the properties to figure out the ideal price so they can optimize their profits.

How I accomplished this: Again, this is very similar to function 2. I just used the same correlation to figure out the estimation for the optimization price.

Code: The code for this can be found in folder location_price, and the details of the function can be found at the bottom of the index.html file.


UI/UX Design:
This website is mainly designed for people who are interested in becoming an Airbnb host. This website is really easy to maneuver around. One can simply type in the geo-locations and beds to figure out their revenue and how to optimize that. Also, one can easily look through the website, and it helps them to decide if they actually want to be a host.


Also, for the layout of the website, I used a template from OS Template.

Thank you very much for reading this! I hope you like it!