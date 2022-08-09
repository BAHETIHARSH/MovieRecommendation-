
# **Abstract**

Recommendation systems have become prevalent in recent years as they dealing with the information overload problem by suggesting users the most relevant products from a massive amount of data. For media product, online collaborative movie recommendations make attempts to assist users to access their preferred movies by capturing precisely similar neighbours among users or movies from their historical common ratings. However, due to the data sparsely, neighbour selecting is getting more difficult with the fast increasing of movies and users. In this paper, a hybrid model-based movie recommendation system which utilizes the improved K-means clustering coupled with genetic algorithms (GA) to partition transformed user space is proposed. It employs principal component analysis (PCA) data reduction technique to dense the movie population space which could reduce the computation complexity in intelligent movie recommendation as well. The experiment results on Movie lens dataset indicate that the proposed approach can provide high performance in terms of accuracy, and generate more reliable and personalized movie recommendations when compared with the existing methods.

# Chapter 1: Introduction


## Problem Statement

Develop a movie recommendation model using the scikit-learn library in python.


##  Project Idea

Movie recommendation is the most widely used application coupled with online multimedia platforms which aims to help customers to access preferred movies. intelligently from a huge movie library. A lot of work has been done both in the academic and industry area in developing new movie recommendation algorithms and extensions. The majority of existing recommendation systems is based on collaborative filtering (CF) mechanism which has been successfully developed in the past few years. It first collects ratings of movies given by individuals and then recommends promising movies to target customer based on the "like-minded" individuals with similar tastes and preferences in the past. There have been many famous online multimedia platforms (e.g., youtube.com, Netflix.com, anddouban.com) incorporated with CF technique to suggest media products to their customers. However, traditional recommendation systems always suffer from some inherent limitations: poor scalability, data sparsity and cold start problems. A number of works have developed model-based approaches to deal with these problems and proved the benefits on prediction accuracy in RS.

 
## Motivation

Recommendation Systems have been in existence for a long time and have served towards convenience of people. In the most general way, recommender systems are algorithms aimed at suggesting relevant items to users(items being books to read, products to buy, music to listen or as in our case, movies to watch.) The most common approach towards recommendation systems has been the Content-based recommendations. Content-based techniques develop representations of clients and items through the investigation of additional data, for example, record content, client proles and the traits of items, to make suggestions

 
## Scope

In many cases, the data that is utilized to build the pictures is difcult to get or even fake; subsequently, its presentation and application run experience the ill effects of signicant restrictions. Thus, we take another approach called as the Collaborative Filtering where instead of only depending upon the attributes of the item, we let our users rate different items and based on such ratings we make recommendations using two ways, either by User-User similarities or Item-Item Similarities.

# Chapter 2: Project Design

 
## H/W , S/W , resources, requirements & their detail explanation

**Hardware Requirement**

  1. RAM (8 GB Minimum)
  2. Hard Disk 1 TB
  3. SSD (Additional, If Possible but not Mandatory)
  4. Graphics Card (Additional, If Possible but not Mandatory)

**Software Requirement**

  1.  Pycharm
  2. Jupyter Notebook
  3. Streamlit
  4. Pandas
  5. Numpy

 
## Dataset Design

_Table 1 Dataset Descrption_

| **Column** | **Description** |
| --- | --- |
| index | Index of row |
| genres | It normally describes a category of Movie |
| keywords | It important words |
| original\_language | Language in which movie produced |
| original\_title | Title of movie in origin country |
| overview | Short description of Movie . |
| production\_companies | Companies which produce the movie |
| production\_countries | Country where the movie is produced |
| spoken\_languages | Languages in which movie is available |
| status | IS movie relesed or in post production |
| tagline | Tagline of movie |
| title | Title of Movie |
| cast | Actor and Actress of movie |
| director | Director of movie |

 
## Hours estimation

7 Days

# Chapter 3: Module Description

 
## Explanation of each module

**COSINE SIMILARITY**

To find similar content for our item, we used the cosine similarity algorithm. The dot product between two vectors is equal to the projection of one of them on the other. Therefore the dot product of two identical vectors is equal to their squared modules. On the other hand if the two vectors do not share any directions, the product will be zero. General formula for calculating dot product is given below:

This dot product is important when defining the similarity as it is directly connected to it. The definition of similarity between two vectors u and v is in fact the ratio between their dot products and product of their magnitudes.

Thus, this will be equal to 1 if the two vectors are identical or it will be 0 if the two are orthogonal.

# Chapter 4: Results & Discussion

 
## Source code 

![img25](https://user-images.githubusercontent.com/65105435/183583258-02b86328-2ffb-49e7-b507-122e25b7c479.jpg)
![img26](https://user-images.githubusercontent.com/65105435/183583272-0c654912-8aac-46e3-9438-d9090cd31b56.jpg)
![img27](https://user-images.githubusercontent.com/65105435/183583274-0d8ce565-5601-4dde-862a-a479b747d06a.jpg)
![img28](https://user-images.githubusercontent.com/65105435/183583279-cdf5eb01-6910-4ab9-8858-9443b59e02c5.jpg)


 
## Screenshots including GUI

 ![image](https://user-images.githubusercontent.com/65105435/183583419-07fadab6-ec8c-4708-bc7e-0d675f6129f7.png)
![image](https://user-images.githubusercontent.com/65105435/183583438-6537f29b-1e2e-40b2-ad85-856043880389.png)
![image](https://user-images.githubusercontent.com/65105435/183583458-1fdbae93-3f5a-4b20-bddd-d967336dd5ee.png)


# Chapter 5: Conclusion

Recommendation systems have become an important part of everyones lives. With the enormous number of movies releasing worldwide every year, people often miss out on some amazing work of arts due to the lack of correct suggestion. Putting machine learning based Recommendation systems into work is thus very important to get the right recommendations. We saw content-based recommendation systems that although may not seem very effective on its own, but when combined with collaborative techniques can solve the cold start problems that collaborative filtering methods face when run independently. Similarly such systems can be improved further by applying neural network embeddings to uplift the quality of recommendations and make them more user personalized.

# References

1. Prince Praveen , Sagar Parmar , Praveen Goud, 2020, Movie Recommendation System Approaches, INTERNATIONAL JOURNAL OF ENGINEERING RESEARCH & TECHNOLOGY (IJERT) Volume 09, Issue 04 (April 2020)

2. [Scikit-learn: Machine Learning in Python](http://jmlr.csail.mit.edu/papers/v12/pedregosa11a.html), Pedregosa _et al._, JMLR 12, pp. 2825-2830, 201 

3. Bird, Steven, Edward Loper and Ewan Klein (2009), _Natural Language Processing with Python_. O'Reilly Media Inc.

4. Jeff Reback, Wes McKinney, jbrockmendel, Joris Van den Bossche, Tom Augspurger, Phillip Cloud, gfyoung, Sinhrks, Adam Klein, Matthew Roeschke, Simon Hawkins, Jeff Tratner, Chang She, William Ayd, Terji Petersen, Marc Garcia, Jeremy Schendel, Andy Hayden, MomIsBestFriend, … Mortada Mehyar. (2020). pandas-dev/pandas: Pandas  0.3 (v 0.3). Zenodo. https://doi.org/10.5281/zenodo.3715232
