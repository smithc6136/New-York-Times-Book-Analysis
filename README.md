# New York Times Book Analysis 
Team Members: Catherine Smith, Jackson Yaggi, Molly Oesterling, Helena O'Farrow 

## Project Description
  For this project, we will be analyzing data from a random list of books from the Google Books Dataset and we will be comparing different aspects of the list including price, publisher, and date to get understand the world of books. 

## Research Questions
  1. Does the number of pages of a book effect the number of the votes that the book recieves? - Molly 
  2. Does the amount of votes affect the overall rating of the book? - Catherine 
  3. Do some publishers produce more expensive books? - Helena 
  4. Do some publishers publish their books during a specific time of the year? - Jackson 
  
## Data Exploration
Searched Kaggle and found a dataset with information on title, author, rating, number of voters, price, publisher, page count, genre, and publish date for approximately 1,000 books.

## Cleanup Process
  *  Removed a row of data that had an error for page count data
  *  Dropped N/A rows
  *  Dropped duplicate rows

## Analysis

### Vote Count vs. Rating - Catherine
#### Question
How does number of ratings impact average rating?
#### Hypothesis
If a book has more ratings, the average rating will be less extreme and have a lower standard deviation.
#### Data Used
Voters and rating for each book, binned by # of voters
#### Findings
As expected, ratings trended towards a more neutral outcome as # of votes increased. Ratings had a higher stdev (less normally distributed) when there were fewer votes. In general, the average rating for a book decreased the more votes it had.

