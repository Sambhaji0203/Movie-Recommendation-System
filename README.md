# Movie Recommendation System
- Data Gathering & Cleaning : Downloading data from kaggle (top 5000 tmdb movies and credits) and combines this files on
 basis of movies title. Columns Such as genres , keywords , actors , crew colums contains messy information and we fetch
only important information from these columns
- Text Preprocessing : Created new column tags from combining all of these . Lowercasing the text , removing the stopwords
  and stem the tags
- Model Building : Transform the all tags into vectors using CountVectorizer(BagofWord) so each movie become a vector and
  calculate the cosine similarity to find the distance and sorting movies according to distance using enumarte to hold index
  of movies .
-  System will recommend 5 movies which are close to selected movies .
-  Recommendation System will reduce average searching time
