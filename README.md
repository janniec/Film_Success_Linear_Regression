# From Book Features to Film Success    
An exercise in linear regression and regularizations.  I was attempting to predict box office gross, scraped from IMDB, of films using data, scrape from Amazon, of books on which the films were based.      

## Data  
Data was collected from the following websites using BeautifulSoup:    
  * [IMDB](http://www.imdb.com/?ref_=nv_home).   
  * [Amazon](https://www.amazon.com/).   
  
## Pipeline  
1. Scrape IMDB    
2. Scrape Amazon    
3. Build linear regression and regularization models  

## Results  
Box office gross of films cannot be predicted from book data. I suspect that there is an inverse relationship, where the success of a film is correlated to an increase in popularity of the book on which the film was based.  

## Next Steps  
  * I could look for other predictive relationships.   
  * I could collect more data.    
    * IMDB did not have Amazon links for older books, like 'The Hobbit', 'Pride & Prejudice', etc. The data showed a skew towards more recent books.  
    * IMDB's Amazon links also linked to older, less popular editions of books. For example, 'Fantastic Beasts & Where to Find Them' had a link to an edition with 4 reviews!! its other editions had 1,000s of reviews.  
  * I could add more features.   
