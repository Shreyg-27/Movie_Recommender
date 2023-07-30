# Movie Recommendation System 

### AIM 

When given a movie as an input, the Machine Learning Algorithm would predict top 5 movies similar to the given input movie by the user. 

### STEPS FOLLOWED 

1) Import numpy and pandas 

2) This is a content based movie recommendation system, so we will take just important columns from dataset like, genres, id, keyword, title, etc. 

3) A dictionary will store all the required columns and data cleansing will also take place- null data + duplicate check 

4) Text Vectorization - It considers movie as a vector and identifies top 5 closest vectors to the given movie. 

5) The stemmer will help in merging same words together. 

6) The recommend function at the end will help in predicting 5 most similar movies.

### RESULTS 

![image](https://github.com/Shreyg-27/Movie_Recommender_System/assets/98229024/25e1e725-36a9-44e9-9994-e59201d3c6fa)

![image](https://github.com/Shreyg-27/Movie_Recommender_System/assets/98229024/d2c50abf-34cb-41b8-ac4b-0ad018051e64)


