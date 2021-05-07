
# Apriori Algorithm

Analyzing shopping trends is a bigdeal in data science, and market-basket analysisis one way in which that's done. Techniques in this subfield seek to understand how buying certain items influence the purchase of other items. This allows retailers to increaserevenueby up-selling or cross-sellingtheir existing customers.

Short stories or tales always help us in understanding a concept better,but this is a true story, Walmart's beer diaper parable. A salesperson from Walmart tried to increase the sales of the store by bundling the products together and giving discounts on them. He bundled bread and jam which made it easy for a customer to find them together.

Furthermore, customers could buy them together because of the discount. To find some more opportunities  and more such products that  can be  tied  together,  the  sales  guy  analyzed all sales  records.  The  two  products  are  obviously unrelated,  so  he  decided  to  dig  deeper.  He found that raising kids is gruelling. And to relieve stress, parents imprudently decided to buy beer.  He  paired  diapers  with  beer  and  the  sales  escalated.  This  is a  perfect  example  of Association Rules in data mining.

It is also known as 
- Market Basket Analysis
- Relationship Mining
- Affinity Analysis

# Association Rules

Association rules are "if-then"statements, that help to show the probability of relationships between  data  items,  within  large  data  sets  in  various  types  of  databases.  Association  rule mining  has severalapplications  and  is  widely  used  to  help  discover sales  correlationsin transactional dataor in medical data sets.

There are two elements of these rules i.e., Antecedent (IF)and Consequent (THEN). But here comes a constraint. Suppose you made a rule about an item, you still have around 9999 items to consider for rule-making. This is where the Apriori Algorithmcomes into play. So, before we understand the Apriori Algorithm, let’s understand the math behind it.

There are 3 ways to measure association:

- Support:
The  probability  that  A  and  B  come  together.  Basically,  support  tells  us  about  the frequently boughtitems or the combination of items bought frequently.

	![Support](https://raw.githubusercontent.com/kasturi-sahu/Apriori-Algorithm/main/Image/support.png "Support")

- Confidence:
The  conditional  probability  of  B  knowing  A.  In  other  words,  how  often  does  B happen when A happens first.

	![Confidence](https://raw.githubusercontent.com/kasturi-sahu/Apriori-Algorithm/main/Image/confidence.png "Confidence")

- Lift:
The ratiobetween support and confidence. A lift of 2 means that the of buying A and B together is 2 times more than the likelihoodof only buying B. Lift indicates the strength of a rule over the random occurrence of A and B.

Lift is to compare confidence with expected confidence.

If an itemset "I" does not satisfy the minimum support threshold, min sup, then "I" is not frequent.

If Lift > 1, then A and B are Positively correlated, Meaning B is likely to be bought if item A is bought

If Lift < 1, then A and B are Negatively correlated, Meaning B is unlikely to be bought if item A is bought

If Lift = 1, then A and B are not correlated, Meaning Occurance of item B is independent of occurance of item A

![lift](https://raw.githubusercontent.com/kasturi-sahu/Apriori-Algorithm/main/Image/lift.png "lift")

# Working with Apriori Algorithm

Apriori  algorithm  is  a  classical  algorithm  in data  mining.  It  is  used  for  mining frequent itemsetsand relevant associationrules. It is devised to operate on a database containing a lot of transactions, for instance, items brought by customers in a store.It is very important for effective Market Basket Analysis and it helps the customers in purchasing their items with more ease which increasesthe sales of the markets.

![](https://raw.githubusercontent.com/kasturi-sahu/Apriori-Algorithm/main/Image/0_PWiIck42-E8z0NbB.png)


# General Steps for Apriori Algorithm

The entire algorithm can be divided into two steps:

- Step 1: 
Apply minimum supportto find all the frequent sets with k items in a database.Use the self-join ruleto find the frequent sets with k+1item with the help of frequent k-item sets. 

- Step 2:
Repeat this process from k=1 to the point when we are unable to apply the self-joinrule. This approach of extending a frequent itemset one at a time is called the “bottom-up” approach.

![](https://raw.githubusercontent.com/kasturi-sahu/Apriori-Algorithm/main/Image/Apriori-Algorithm.jpg)

# Shortcomings

- It  requires extensive computation;  if  the  item  sets  are  very  large  and  the  minimum support is kept very low.
- The   algorithm   scans   the   database   too   many   times,   which   reduces   the   overall performance.
- The time and space complexity of this algorithm is very high.

# Applications

The following are the some of the applications where Apriori is widely used:

- Recommender system in some of the Ecommerce companies.
- Auto omplete feature by a search engine.
- Finding association in the student's database, patients database, etc

# References

- [Weekly Data Science: The Apriori Algorithm](http://https://www.youtube.com/watch?v=2oVMmMdeCOQ "Weekly Data Science: The Apriori Algorithm")
- [Association Rule Mining via Apriori Algorithm in Python](http://https://stackabuse.com/association-rule-mining-via-apriori-algorithm-in-python/ "Association Rule Mining via Apriori Algorithm in Python")
- [Apriori Algorithm | Mining of Massive Datasets ](http://https://www.youtube.com/watch?v=tY1JE6XFjCY "Apriori Algorithm | Mining of Massive Datasets ")

# Additional Resources

- [Application of an improved Apriori algorithm in a mobile e-commerce ](http://https://www.emerald.com/insight/content/doi/10.1108/IMDS-03-2016-0094/full/html "Application of an improved Apriori algorithm in a mobile e-commerce ")
- [Recommendation of Books Using Improved Apriori Algorithm](http://http://www.ijirst.org/articles/IJIRSTV1I4050.pdf "Recommendation of Books Using Improved Apriori Algorithm")
- [WebApriori: A Web Application for Association Rules Mining](http://https://link.springer.com/chapter/10.1007%2F978-3-030-49663-0_44 "WebApriori: A Web Application for Association Rules Mining")
- [Web Behavior Analytics ](http://https://medium.com/@jameschen_78678/web-behavior-analytics-104-66e2de0bf9a9 "Web Behavior Analytics ")
- [A Novel Web Fraud Detection Technique using Association Rule Mining](http://https://www.sciencedirect.com/science/article/pii/S1877050917319634 "A Novel Web Fraud Detection Technique using Association Rule Mining")




[========]

# Notes 

![](https://raw.githubusercontent.com/kasturi-sahu/Apriori-Algorithm/main/Image/1.jpg)

![](https://raw.githubusercontent.com/kasturi-sahu/Apriori-Algorithm/main/Image/2.jpg)

![](https://raw.githubusercontent.com/kasturi-sahu/Apriori-Algorithm/main/Image/3.jpg)



