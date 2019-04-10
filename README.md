# What features contribute to the Gross Box Office Earnings?

Many a time, people have faced this unavoidable problem: the movie has a poor ranking so should he or she see it regardless? While this problem may be trivial, our motivation for our project stems from figuring out what factors contribute to a box office movie. 

Is it the director, actors, production company, movie genre, or MPAA rating which heavily influence the gross? 


# Dataset: 
We obtained a dataset of 5,044 different movies and 28 quantitative features per each movie. Our main variable of interest is gross, which indicates if the movie was a hit or not. We are interested in determining which qualitative (or quantitative?) features are the best indicators for whether a movie faired well at the box office or not. Thus, our chosen attributes must be easily identifiable by the untrained moviegoer. We define the following variables with their corresponding potential value in our dataset:
Gross 
IMDB Rating—a number from 1 to 10
Genre

Actor
Director
Color (Black or White) 
Number of Critics for positive reviews
Duration 
Actor 3 Facebook Likes
Actor 2 Name
Actor 1 Facebook Likes
Actor 1 Name
Movie Title
Number of Users who voted
Cast total
Director Facebook Likes
Actor 3 Name
Plot Keywords
Number of positive IMDB reviews
Language 
Country
Content Rating
Budget 
Title Year
Actor 2 Facebook Likes
Movie FaceBook Likes

Found on (TMDB 5000 Movie Dataset)[https://www.kaggle.com/tmdb/tmdb-movie-metadata]
(Inside data folder)

# Requirements to Run: 

Scikit-Learn
NumPy
matplotlib
sklearn

#Files:
Inside folder "Scripts," are the scripts we ran for our study. Highlights include: silhouette analysis used for Kmeans, and Decision Tree Regression performed. Got some interesting findings. 

# Conclusion: 
LOW-BUDGET DIRECTORS: PLEASE SEE OUR STUDY!

Most important contributing factors for success: Actor 1 Facebook Likes, Director Name
Least important: Aspect-ratio

GO SEE AVENGERS: ENDGAME!

# Contributing: 
Sambit Panda
Thomas Keady

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.


## License
[MIT](https://choosealicense.com/licenses/mit/)



