# Airbnb-data-analysis

# Part 1
There are 10 basic data science questions for us to learn about the dataset.  
* (1) How many unique listings are there in the LA dataset? How many unique hosts are there?
* (2) What is the mean, median, standard deviation, minimum and maximum of the number of listings per host in LA?
* (3) What is the average and standard deviation number of listings for a super host versus a non-super host? Does super host or non-super host have more listings on average?
* (4) What are the unique types of host verifications are there?
* (5) What are the five most popular verification types of hosts? For each type of the top five verifications, how many percent of hosts verify that type?
* (6) What is the mean, standard deviation of the average price of a listing in Los Angles from 01/01/2020 to 03/01/2020 (inclusive)?
* (7) For reviews that are written in Jan, 2016, what are the most popular ten words except stopping words? What about reviews written in March, 2017 and April, 2018?
* (8) Which five zipcode has the highest average listing price and has at least 30 listings (again only considering available dates) between 2020-01-01 to 2020-02-01 (inclusive)? What are these listing prices? What are the number of active listings and number of hosts in these top five zipcodes (a listing is active if it has at least one available date in the calendar data)?
* (9) Focusing on the data from 2020-01-01 to 2020-04-01 (inclusive), what are five zipcodes that have at least 30 listings and have the largest absolute difference between the average prices on weekends versus the average prices on weekdays? (Weekends = Saturday and Sunday).
* (10)What is the average and standard deviation of the daily total capacity at Airbnb Los Angeles from 2020-01-01 to 2020-04-01? The daily total capacity in a day is the number of beds that are available in that given date. What is the average and standard deviation of the daily price per bed at Airbnb Los Angeles from 2020-01-01 to 2020-04-01?

# Part 2
We also brought up 5 interesting business questions to dig more insights of the datasets  
## Questions
Question 1:How does the average daily listing price change with the date from 2019-09-14?  
Question 2:what are the 10 most flourishing neightborhood? Any ideas why?  
Question 3:Which neighbourhoods are becoming more popular in recent years?  
Question 4:Is there any difference in review top words above or below the average review rating?  
Question 5:How is the average review scores difference between different property and room types?  

## Executive summary
First, we look at how the average daily listing price change with the date. Overall there is a fluctuation in the average daily listings price, and the price is increasing moderately. As we can see, dates around Christmas have significantly high average prices, which is quite reasonable. There is also a predicted high price on April 28th, 2020. Hosts may get more revenue on specific holidays.


Then we are interested in how location influences Airbnb's business. After analyzing the data, we find that the top 10 flourishing neighborhoods are Venice, Hollywood, Downtown, Long Beach, Santa Monica, Hollywood Hills, Westlake, Koreatown, Mid-Wilshire, and West Hollywood, which have the largest number of listings. All of them are famous travel spots, which appeals to tourists from all over the world. The prosperous tourism industry promotes local accommodation businesses like Airbnb.  


To take a closer look at the most popular locations, In question 3, we use the number of reviews in each year as a measurement of region popularity. The reviews per listing at Long Beach and downtown keep increasing in recent years and the number of total reviews has better-increasing speed. Therefore, we believe Long beach and Downtown are the most business potential community.


In Question 4, we try to find the difference between reviews of high-score hosts and lower-score hosts. In the top twenty words of these two kind are similar, but the reviews of lower-score host contains "parking". So we check the percentage of high-score hosts and lower-score hosts providing free parking. It shows the percentage of high-score hosts providing free parking is higher. Therefore, whether hosts offer free-parking may influence their rating score.  


When it comes to rating difference in different property/room types, we can see the property type of different room types are significantly different. The variance of ratings in the private room is more than the entire home/apt, and have some strange low scores. Airbnb should focus more on the control of hosts providing private-room listings.
