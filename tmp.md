## ideas for analysis

- analyze founders to see which ones are most successful
  - analyze ones in different areas, see how successful they each are, probably base success off of amount raised? should compare this to average in their respected areas in order to see which founders stand out compared to the general ones check out which ones founded multiple startups here, etc.
- analyze investors

  - see which ones give the most money
  - see which ones invest the most, moneywise, and by number of companies they invested in
  - take some sort of approximation of how good investors are based on how good the companies they invest in are, possibly compare it to actual investor data if that can be found

- analyze companies based on their data
  - compare different metrics for success: status (operating, exited, dead, etc) amount raised more detailed information than what's given about amount raised? - can analyze it by investor based on seed-db data and then get better data about investors, can do the same with crunchbase
  - compare different headquarters locations, chart on a map and see average amount raised
  - compare year founded to amount raised, possible that older companies get more money or something like that
  - analyze average y-combinator year+session to see distribution of how much money was given on average
  - analyze different categories, see how profitable each category is also see how risky a category is based on how many companies in that category died
  - do something based on the description of a company? possibly feed all of them into llama2 and ask it how it would rate it as a startup in 2023 and see if that's correlated to success somehow?

# Project structure

- Just about a paragraph, explaining the data source, contents (columns, etc.)

- Take a look at the columns, see what's in the dataset in general

  - figure out which ones are the basic numerical ones
    - just draw some general distributions for them
  - for the categorical ones, just list out some categorical plots
    - have some countplots, barplots sorted by the category type, etc.
  - for the dates and similar stuff, also have some distributions over time, possibly do the same for months, etc.

- Generally good to get a rough idea of the distribution, pay attention to outliers and try to analyze them later
- Probably worth paying attention to amount of data available over time, etc., possibly cut off some data from last year if analyzing by year, possibly cut off earlier years, etc.
- Probably generally good idea to look at some maxiumums as well as averages occasionally
- When dealing with geographic data, probably a good idea to draw a distribution of whatever we're measuring on a map to get a sense of distribution

- Maybe try to do some random stuff like scraping
