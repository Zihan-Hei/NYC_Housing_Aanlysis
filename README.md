# Affordable Housing Analysis for Low-Income Families


# Introduction
We are local real estate agents looking for low cost housing for families. Our overall goal is to find affordable housing for families, particularly small, low-income families. We hope to look at all neighborhoods and cities and determine where our clients could move to at an affordable price. The dataset has columns such as price, city, amenities, and bedrooms/bathrooms just to name a few; by analyzing this data, we as real estate agents can find low cost housing for families that has everything they are looking for.

This dataset was gathered by Yash Patel, and donated to the UCI Repository on 12/25/2019. The data was collected from multiple online classified listings, scraping the data and taking note of common real estate attributes, and structured to accomodate for machine learning excersizes. It contains 22 attributes, such as rental price, square footage, number of bathrooms and bedrooms, amenities, location details (latitude, longitude, city, state), and other descriptive data like title and category. The UCI Machine Learning Repository is a publicly available resource that houses many datasets such as this one, for the empirical analysis of machine learning algorithms.

We will analyze our data through these questions:

1. How accurately can we determine price from square footage, is there a significant correlation? This would involve performing a linear regression, as we would like to confirm whether we can make fair assumptions about the cost of an apartment, looking at square footage and holding other factors constant. This would make apartment cost estimates easier for our clients and would also help us give them a reality-check regarding how much space they can realistically afford.

2. Can we accurately classify rental properties as “affordable” or “unaffordable” for low-income households in NYC based on a set price $1100 threshold and property attributes? This would involve classification such as logistic regression, by creating a model that effectively distinguishes between "affordable" and "unaffordable" properties. This would help us identify the right options for our clients within their budget constraints.

3. How many apartments in a specific city (nyc) have at least 2 bedrooms and 1 bath for less than $1500 per month? This would involve making a graph, moat likely a count graph, to see the total amount of apartments that meet this criteria. Having this information would help our clients narrow down their search for affordable housing in NYC that has some space.

4. Is there easy access to "affordable" housing in NYC? What neighborhoods/where should we direct new homeowners to? This would involve mapping the apartment locations onto a map of NYC to see the spatial relations of the apartments we deem "affordable" and "unaffordable" to see where cheaper and more expensive apartments tend to be located. This would help us to pick apartments to market to our target audience or even to find neighborhoods that we could hone in on for advertising.

5. Can it be determined if prices are affected by owning pets? How much of an effect does owning a pet have on affordable housing? This would involve logistic regression by creating a model where we can examine the variables by using the p-value and the coefficent. If the coefficent is positive then that means that owning a pet increases the price of the apartment. If its negative, then that means owning a pet decrease the price of the apartment. Having this information on hand would help our clients with pets find housing at an affordable price.

