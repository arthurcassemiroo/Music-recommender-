<h1 align="center"> Music recommender with Python <img src='https://cdn-icons-png.flaticon.com/512/5968/5968350.png' width=30 height=30> </h1>

## Music recommender created using python, machine learning methods and spotipy library.

### <strong> How it works? </strong>
The recommender works through machine learning process and using the data to calculate the distances between the songs with the attributes that differentiate them from each other. The Spotipy library is used so that the data will be brought from there (the images that will be used to make the recommender more user-friendly and visible).

### <strong> Methods used in project </strong>
* Standard Scaler;
* PCA; 
* Pipeline;
* One Hot Encoder;
* K-means;
* Euclidean distance.

### <strong> Prerequisites </strong>
* Have an account in google collab to run the notebook. 

### <img align='center' src='https://cdn-icons-png.flaticon.com/512/4201/4201973.png' width=30 height=30> <strong> Important warning </strong>
For the recommender to work without errors, it is necessary that the name of the song is written correctly, as it is in the dataset. An example follows below.

```python
recommender('Dua Lipa - Levitating')
```

Preview: 
![image](https://user-images.githubusercontent.com/88465565/211456960-d67a4083-1b55-49b8-bc72-5a87db2774dc.png)
