# Movie Recommendation System 

# Content-Based Movie Recommendation System -
This type of recommendation engine works on the concept that if a user liked a particular movie, he/she might like a movie similar to it based on attributes such as genre, director, actors etc.

![image](https://user-images.githubusercontent.com/90978030/170785934-3a3aabc1-125f-419c-adc3-358e861b7eec.png)


# Movie Recommendation System based on CountVectorizer and cosine similarity function 

### Cosine Similarity : 
   Cosine similarity is a measure used to determine the similarity between two vectors in a high-dimensional space. It calculates the cosine of the angle between the two vectors and returns a value between -1 and 1.

![image](https://user-images.githubusercontent.com/78251168/227769415-0367c033-f3fe-4b32-bf5d-36d05879e3fc.png)


In simpler terms, imagine two vectors as arrows pointing in a particular direction. The angle between these arrows can be used to measure their similarity. If the arrows are pointing in the same direction, then the angle between them is 0 and the cosine similarity is 1. If the arrows are perpendicular, the cosine similarity is 0, and if the arrows are pointing in opposite directions, the cosine similarity is -1.

Cosine similarity is commonly used in information retrieval and text mining to compare the similarity of documents or text snippets based on the frequency of words. It is also used in recommendation systems to find similar items or products.

### CountVectorizer  
   CountVectorizer is a great tool provided by the scikit-learn library in Python. It is used to transform a given text into a vector on the basis of the frequency (count) of each word that occurs in the entire text. This is helpful when we have multiple such texts, and we wish to convert each word in each text into vectors (for using in further text analysis). 


# IDE's used -
1. Jupyter Notebook
2. PyCharm Community Edition 2022.1.1

# Dependencies -
1. pandas
2. numpy
3. scikit-learn
4. nltk
5. streamlit
6. requests
7. streamlit
8. pickle



# Make some changes to the code you just cloned and deploy them to Heroku using Git.

$ git add .
$ git commit -am "make it better"
$ git push heroku master

# Deployment method 
 
Deploying using AWS "ec2-15-206-70-92.ap-south-1.compute.amazonaws.com:8501"
