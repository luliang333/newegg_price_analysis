# CPU Price Analysis
## Newegg vs Best Buy

#### * To get the CPU prices from two companies, I used BeatifulSoup to scrape the data from their websites. 

#### * Next,I used pandas library to clean the data so that I get two dataframes contains columns 'CPU Models'(object) and 'Prices'(float) for each companies. Then I saved them into two seperate CSV files.

#### * Then I used Postgress to inner join the two tables together on 'CPU Models'. It turns out there are 20 CPUs that two companies are selling at the same time.

#### * I used Tableau to visualize the data. As the result, Newegg had 15 out 20 CPUs cheaper than Best Buy. On average, the CPU on Newegg's website are $6 dollars cheaper than they're on Best Buy's website.
