
# Kings County Housing Linear Regression

## The Questions answered within the notebooks and power point slides
Question 1: Which day of the week do most sales take place?
Answer: Tuesday

Question 2: How are the houses spread out geographically in regards to ordinal variables such as grade, condition, number of floors, and view? I wanted to use the latitude and longitude data for something, so at this point I had to learn how to graph it. It may be worth noting here that on top of the Flatiron curriculum I set aside a bit of time every day to read articles on data visualization, and try to go through at least 1 datacamp tutorial a day.

Question 3: Where are the waterfront properties located geographically? Is this data reliable and accurate?
Answer: No
Many of these properties are located far inland. This data is bogus and therefore I removed the feature.

## Exploring the data

While exploring the data setI am looking for placeholders, as well as getting a general sense of what information is recorded and how. I particularly like using df.sample() since I figured the instructors were likely to add anomalies that were not within the first or last 10 rows. Running df.sample(20) a few times allowed me to randomly glance around the data as if I were skimming a book.

From here I took note of which columns contained null values, placeholders, too many zeros, incorrect data types.
Before actually cleaning the data I needed more information about each column. The project itself contained an additional file within the github repository, I just needed to load it. And Kings County Washington had a useful website https://info.kingcounty.gov/assessor/esales/Glossary.aspx?type=r#g I referenced often while looking at each feature.

## Scrubbing 
I dealt with cleaning the data set through extensive exploration that involved a lot of data visualization. Therefore, the load times may be quite a bit longer than my other projects when trying to view the jupiter notebooks.  However, there were several unique visualizations I was able to create using the GPS coordinates of the houses which where bought and sold in Kings County.  

## The Dataset

For this project, you'll be working with the King County House Sales dataset. We've modified the dataset to make it a bit more fun and challenging.  The dataset can be found in the file `"kc_house_data.csv"`, in this repo. 

The description of the column names can be found in the column_names.md file in this repository. As with most real world data sets, the coliumn names are not perfectly described, so you'll have to do some research or use your best judgement if you have questions relating to what the data means.

You'll clean, explore, and model this dataset with a multivariate linear regression to predict the sale price of houses as accurately as possible. 

