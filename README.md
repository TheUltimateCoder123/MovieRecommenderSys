## Movie Recommender System using Streamlit
This Recommends movie that are much similar to each other based on Cosine distance.

## Details
- Content Based that recommends movies on the basis of similarity.
- First Text is preprocessed, stop Words are removed and the CountVectorizer was applied to create the vectors in Dimensional Space.
- For this Purpose, BagOfWord is created combining all the words. 
- To determine the distance between one movie with the other the Cosine distance.

![cosine](https://user-images.githubusercontent.com/73277254/219680378-8f857392-414c-4529-ad35-313047eb22d4.png)




## Technology Used
- Streamlit
- Numpy 
- Pandas
- NLTK
- Scikit-learn


## ScreenShot
![chhhh](https://user-images.githubusercontent.com/73277254/219680471-65065d1e-f736-42a1-8f3f-2a3a7d0f1da0.png)

## How to run :
- First install Requirements.txt :
````   pip install -r requirements.txt  ````
- second run The app using Following Commands :
```` streamlit run app.py ````
