# Recommender System

Nowadays, people buy products from onlinemore than from stores. Previously, people used to  purchase  products  based  on  the reviews  givenby  relatives  or  friends,  but  now  as  the options have increased and we can buy anything digitally, we need to assure people that the product  is  of  good  quality  and  they  will  like  it.  To  give confidence in  buying  products, recommender systems were built.

Recommender  systems  are  one  of  the  most  successful  and widespread applications  of machine learning technologies. Recommender systems help businesses to increase revenue and help customers to buy the most suitable product for them.

![](https://raw.githubusercontent.com/kasturi-sahu/Recommender-System/main/Images/3.png)

# What is a Recommender System?

Recommender system filters out the products that a particular customer would be interested in  or  would  buy  based  onhis  or  her previous buying history.  The  more  data  are  available about a customer the more accurate the recommendations. But if the customer is new, then this method will fail as we have no previous data for that customer. So, to tackle this issue different methods are used; for example, often the most popular products are recommended. 

These  recommendations  would  not  be  necessarily  accurate  as  they  are  not  customer dependent and are the same for all new customers. Some businesses ask new customers their interests so that they can recommend more precisely.

# Types of recommender system

![](https://raw.githubusercontent.com/kasturi-sahu/Recommender-System/main/Images/1.png)


# Terms Used in Recommender Systems

## Document Vectors:
- To build a relation between different texts we need pairwise similarity metric.
- Document  vectors  represent  these  texts  into  a vector  spaceso  that  we  can  derive  a relation between them.
- Click on the [link](http://https://www.youtube.com/watch?v=dkPZXMonTLA "link") to get more information about document vectors.

## TF-IDF:

- It is a measure used to evaluate how important a word is to a document in a document corpus.
- The importance of words increases proportionally to the number of times a word appears in the document.
- To get more information about the TF-IDF vectorizer click [here](http://https://www.youtube.com/watch?v=D2V1okCEsiE "here").

**Formula**:

![TFIDF](https://raw.githubusercontent.com/kasturi-sahu/Recommender-System/main/Images/TFIDF.png "TFIDF")

## Cosine Similarity:

- It is a similarity measure that estimatesthe cosine angle between the profile vector and item vector, i.e., cosine similarity.
- The cosine score can take any value between -1 and 1. The higher the cosine score, the more similar the documents are to each other.

- To get more information about cosine similarity click [here](http://https://www.youtube.com/watch?v=5lvS8078ykA "here").

![Cosine Similarity](https://raw.githubusercontent.com/kasturi-sahu/Recommender-System/main/Images/Cosine%20similarity1.jpg "Cosine Similarity")

# Content –based Filtering

This filtering is based on the description or some data provided for that product. The system finds the similarity between products based on its context or description. The user's previous historyis considered to find similar products the user may like. For example, if a user likes movies such as‘Mission Impossible’ then we can recommend him the movies of 'Tom Cruise' or movies with the genre 'Action'. In this filtering, two types of data are used. First, the likes of the user, the user's  interest,  user's personal information such as age, or sometimes the user's history too. This data is represented  by  the user  vector. Second, information related to the product's known as an item  vector.  The  item  vector  contains  the  features  of  all  items  based  on  which similarity between them can be calculated.

![](https://raw.githubusercontent.com/kasturi-sahu/Recommender-System/main/Images/2.png)


# Collaborative –based Filtering

Collaborative filtering is a technique that can filter out items that a user might like based on reactions by similar users. It works by searching a large group of people and finding a smaller set of users with tastes similar to a particular user. It looks at the items they like and combines them to create a ranked list of suggestions. There are many ways to decide which users are similar and combine their choices to create a list of recommendations. For example, if the user ‘A’ likes ‘Coldplay’, ‘The Linkin Park’ and ‘Britney Spears’ while the user ‘B’ likes ‘Coldplay’, ‘The Linkin Park’ and ‘Taylor Swift’ then they have similar interests. So, there is a huge probability that the user ‘A’ would like ‘Taylor Swift’ and the user ‘B’ would like ‘Britney Spears’. This is the way collaborative filtering is done

![Collaborative](https://raw.githubusercontent.com/kasturi-sahu/Recommender-System/main/Images/Collaborative%20filter.png "Collaborative")


# Collaborative Filtering Types
- User-based collaborative filtering
- Item-based collaborative filtering

## User –based Collaborative Filtering:

The main idea is that you are given a matrix of preferences by users for items, and these are used to predict missing preferences and recommend items with high predictions. One of the key  advantages  of  this  approach  is  that  there  has  been  a  huge  amount  of  research  into collaborative  filtering,   making   it   well   understood,   with   existing   libraries   that   make implementation  fairly  straightforward.  Another  important  advantage  is  that  collaborative filtering is independentof itemproperties. All you need to get started is user and item IDs, and some notion of preference by users for items (ratings, views, etc.)

## Item –based Collaborative Filtering:

Item-Item collaborative filtering looksfor items that are similar to the articles that the userhas already rated and recommended most similar articles. But what does that mean when we say  item-item similarity? In this case, we don't mean whether two items are the same by attributes like apple and orange are similar because both are fruits. Instead, what similarity means is how people treat two items the same in terms of like and dislike.

This  method  is  quite stableas  compared  to user-based  collaborative  filtering  because  the average  item  has a lot more ratings than the average user. So, an individual rating doesn't impact  as  much.Collaborative  filtering  (CF)  is  a  very  popular  recommendation  system algorithm  for  the  prediction  and  recommendation  based  on  other user's ratings and collaboration.   User-based   collaborative   filtering   was   the   first   automated   collaborative filtering mechanism. It is also called KNN collaborative filtering.

![](https://raw.githubusercontent.com/kasturi-sahu/Recommender-System/main/Images/User-Item.jpeg)


------------

![](https://raw.githubusercontent.com/kasturi-sahu/Recommender-System/main/Images/collaborative.jpg)

# Benefits of Recommender System

Below  are  some  of  the  various  potential  benefits  of  recommendation  systems  in  business, and thecompanies that use them:

1. Improving with use (retention):  One of the core potential benefits of recommendation systems  is  their  ability  to continuously  calibrateto  the preferencesof  the  user.  This makes products become more and more “sticky” in their customer retention as time goes on. You’re much less likely to switch to a Netflix competitor when Netflix has such a wonderful sense of which movies and shows you might want to watchnext well.
Because most of Netflix’s revenues come from a fixed-raterecurring  billing  model subscription,  the  company’s  biggest  ROI  “win”  with  recommendation  systems  is retention. 

2. Improving cart value:  A company with an inventory of thousands and thousands of items would be hard-pressed to hard-codeproduct suggestions for all of its products, and such static suggestions would quickly be out-of-dateor irrelevant for many customers. By using various means of “filtering”, e-commerce giants can find opportune times to suggest (on their site, via email, or through other means) new products that you’re likely to buy. 

- Amazon’s quick delivery and emphasis on customer service have earned them millions of customers.
- Recommendation engines play a role not only in helping customers find more of what they  need  (and  see  Amazon  as  an  authority),  but  these  systems  also  improve  cart value. 
- If Amazon doesn’thave to pay much more for shipping to send you two or three times as many products, their profit margins improve.

3. Improved  engagement  and  delight: Sometimes seeing an ROI doesn’t involve explicitly asking   for   payment.   Many   companies   use   these   systems   to   simply encourage engagementand activity on their product or platform.

- YouTube has subscription options, but the majority of the firm’s revenues are driven by  advertisements  placed  across  its  wide  array  of  video  properties.  The  company makes more money whenusers come back time and time again.
- YouTube doesn’t optimizefor short-termview length, as this might encourage pushy or flashy tactics that wouldn’t genuinely delight users. Instead, the service aims to encourage long-termuse,  because  advertising  views  is  the  ROI  that  these  systems serve at YouTube.
- Facebook  is  another  obvious  example  of  a  similar  application  of  recommendation engines.

# Real-World Applications
- Amazon
- Netflix
- Spotify
- YouTube

# Conclusion

Over  the  years,  machine  learning  has  solved  several  challenges  for  companies  like  Netflix, Amazon,  Facebook,  etc.  The  recommender  system  for  Netflix  helps  the  user  filter  through information in a massive list of movies and shows based on his/her choice. A recommender system must interact with the users to learn their preferences to provide recommendations. The recommender system is as murky as data science. Just like data science, the boundaries of recommender systems are hard to define and they are sometimes over-hyped. This hype may lead to people investing in a recommender system they don't really need, just like the common issue of premature investment in data science. However, the hype is based on real value, which can definitely be delivered by recommender systems when they are used correctly. To get more information about recommender systems, click [here](http://https://www.youtube.com/watch?v=Eeg1DEeWUjA "here").

# Additional Resources

[Build A Recommendation Engine in One Day](http://https://blog.dataiku.com/build-a-recommendation-engine-in-one-day "Build A Recommendation Engine in One Day")

[The Top 112 Recommender System Open Source Projects](http://https://awesomeopensource.com/projects/recommender-system "The Top 112 Recommender System Open Source Projects")

[5 Open-Source Recommender Systems ](http://https://analyticsindiamag.com/5-open-source-recommender-systems-you-should-try-for-your-next-project/ "5 Open-Source Recommender Systems ")

[Building a COVID-19 Project Recommendation System](http://https://towardsdatascience.com/building-a-covid-19-project-recommendation-system-4607806923b9 "Building a COVID-19 Project Recommendation System")

[How to design Recommendation system,that resembling the Amazon](http://https://madasamy.medium.com/introduction-to-recommendation-systems-and-how-to-design-recommendation-system-that-resembling-the-9ac167e30e95 "Introduction to recommendation systems and How to design Recommendation system,that resembling the Amazon")

# Research Papers

[Online Recommendation System](http://https://scholarworks.sjsu.edu/cgi/viewcontent.cgi?article=1096&context=etd_projects "Online Recommendation System")

[Recommender Systems and User Modeling based on Mind Maps](http://https://arxiv.org/ftp/arxiv/papers/1703/1703.09109.pdf "Recommender Systems and User Modeling based on Mind Maps")

[A collaborative approach for research paper recommender system](http://https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5628815/ "A collaborative approach for research paper recommender system")



[========]



# Notes 

![](https://raw.githubusercontent.com/kasturi-sahu/Recommender-System/main/Images/1.jpg)

![](https://raw.githubusercontent.com/kasturi-sahu/Recommender-System/main/Images/2.jpg)

![](https://raw.githubusercontent.com/kasturi-sahu/Recommender-System/main/Images/3.jpg)

![](https://raw.githubusercontent.com/kasturi-sahu/Recommender-System/main/Images/4.jpg)

![](https://raw.githubusercontent.com/kasturi-sahu/Recommender-System/main/Images/5.jpg)

