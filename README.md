
# AI-Powered Movie Recommendation System

This project implements a content-based recommendation system using the MovieLens dataset.
The system recommends movies based on title similarity and genre similarity using TF-IDF vectorization and cosine similarity.




## Features

✅ Data Preprocessing: Cleans movie titles, splits multiple genres, and removes movies without genres.

✅ Exploratory Analysis: Counts movies per genre and visualizes them.

✅ Search by Title: Finds similar movies based on title using TF-IDF.

✅ Genre-based Recommendation: Suggests similar movies based on genre similarity.

✅ Interactive User Input: Users can enter a movie title and get personalized recommendations


## Data set

The project uses the **MovieLens dataset** (`movies.csv.zip`).  
Each movie entry contains:  
  `movieId` → Unique ID for each movie  
  `title` → Movie title  
  `genres` → List of genres (Action, Adventure, Drama, etc.)  
## Tech Stack

 **Python**  
 **Pandas** – Data handling  
 **Matplotlib** – Visualization  
 **Scikit-learn** – TF-IDF Vectorizer & Cosine Similarity  

## How it works

1. Load and clean the dataset.  
2. Convert movie titles and genres into **TF-IDF vectors**.  
3. Compute similarity scores using **cosine similarity**.  
4. Allow user to search movies by title.  
5. Recommend similar movies based on **genre similarity**. 
## Example usage

```bash
Enter a movie title: Interstellar
Matching titles found:
0: Interstellar

Recommendation results based on genre similarity:
- Gravity (Sci-Fi, Adventure)
- The Martian (Sci-Fi, Drama)
- Inception (Sci-Fi, Action)
...
```

---

## Future Improvements

🔹 Add user ratings for collaborative filtering.  
🔹 Deploy the system as a **Streamlit web app**.  
🔹 Combine genres, ratings, and keywords for hybrid recommendations.
## Screenshots

<img width="1333" height="567" alt="Screenshot (26)" src="https://github.com/user-attachments/assets/3f7f37b5-5ad4-4d89-913d-cc75a35a7fb9" />
<img width="1339" height="563" alt="Screenshot (27)" src="https://github.com/user-attachments/assets/caa78172-e9bf-453d-a834-96d2507873fd" />
<img width="1337" height="560" alt="Screenshot (28)" src="https://github.com/user-attachments/assets/5ca74642-5fdd-406d-a1db-f1464907e399" />
<img width="1335" height="559" alt="Screenshot (29)" src="https://github.com/user-attachments/assets/b9cbec07-881d-45b6-a70c-cad6bdd16c5b" />
<img width="1335" height="558" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/644f6b55-fa5f-4ce8-992e-0ac2c3c2b799" />
<img width="1335" height="565" alt="Screenshot (31)" src="https://github.com/user-attachments/assets/05b5d4f9-22cf-4538-92ed-27fb2d9d5743" />
<img width="1337" height="564" alt="Screenshot (32)" src="https://github.com/user-attachments/assets/4ec08b80-40db-4b22-94a6-402792433532" />
<img width="1331" height="562" alt="Screenshot (33)" src="https://github.com/user-attachments/assets/de2e215d-806a-407a-a172-cfdf0333c813" />
<img width="1333" height="565" alt="Screenshot (34)" src="https://github.com/user-attachments/assets/1db771e5-b78a-41f6-86d8-2f90c62e9c9b" />
<img width="1333" height="564" alt="Screenshot (35)" src="https://github.com/user-attachments/assets/931f8a48-2a04-4f1f-99a9-f8a8f454a87e" />
<img width="1333" height="559" alt="Screenshot (36)" src="https://github.com/user-attachments/assets/3cdf1e17-4ebe-4e5c-80ac-2c91467a8cf3" />
<img width="1337" height="560" alt="Screenshot (37)" src="https://github.com/user-attachments/assets/58a7ae5e-5b8d-441d-aa7f-67d81a2f1e8e" />
<img width="1335" height="556" alt="Screenshot (38)" src="https://github.com/user-attachments/assets/1c786320-3298-4d95-bc20-abe0ddd6fd18" />
<img width="1335" height="556" alt="Screenshot (41)" src="https://github.com/user-attachments/assets/9d45915e-130d-4d13-a6c3-35daed0894ae" />
<img width="1333" height="562" alt="Screenshot (42)" src="https://github.com/user-attachments/assets/45fe6c87-d68f-417c-9f11-8e8b691fa8ab" />

