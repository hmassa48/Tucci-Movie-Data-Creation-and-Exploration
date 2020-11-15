# Stanley Tucci a Theatrical Genius
It should be no surprise to anyone that Stanley Tucci is the most influential actor of our time. There is absolutely nothing that man cannot play. He is a bald-headed genius with an aptitude for creativity and flair that others just cannot copy. So, it was nothing less than absolutely flooring during this week's episode of me being trapped in my parent's house that my dad confused the saving grace of this generation for Howie Mandell of America's Got Talent. 
So, I decided to work on this quick personal project to explore the depths of Stanley Tucci's talent, asking the question:
### Is there anything he can't do ? 

## Data Scraping 

This project uses Stanley Tucci's wikipedia page as reference for his movie appearances. From this set up of movies, three different datasets were created. The first dataset was created from information box scraped off of each of the movie's wikipedia page. This dataset contains information like each movie's stars, budget, box office earnings and more. The next dataset was added onto the previous dataset. This next dataset was created using the rotten tomatoes API for each movie. Finally, the third dataset was created from the original Wikipedia page of each movie. This dataset contains a corpus describing each of Stanley Tucci's movie. The Wikipedia page was scraped for sections containing the header 'Plot' or 'Synopsis', if there is no section then the introductory section of the Wikipedia page is added into the corpus instead. 


## Data Cleaning

