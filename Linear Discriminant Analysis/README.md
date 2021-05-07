# Introduction to Linear Discriminant Analysis

Linear  Discriminant  Analysis  (LDA)  is  a dimensionality  reduction method,  justlike  Principal Component Analysis (PCA). However, both are quite different in the approaches they are used to  reduce  dimensionality.  PCA  chooses  new  axes  for  dimensions  such  that variance (and hence the ‘shape')  of the data  is  preserved,  while  LDA  chooses new  axes  such  that the separability between two classes is optimized. When one discusses using dimensionality reduction,  not  for  visualization  purposes  but  to increase model  performance,  usually  they are talking about LDA. The  LDA  tries  to  project  the  features  residing  in higher  dimensional space  onto a  lower-dimensional space  to  reduce  resource  computation.  This  helps  us  in  avoiding  the  curse  of dimensionality. 

LDA  is  a supervised classification  technique,  and  it  is  considered  a  part  of crafting  competitive  machine  learning  models.  It  is  widely  used  in  areas  such  as  image recognition and predictive analysis in marketing, etc.

![](https://raw.githubusercontent.com/kasturi-sahu/Linear-Discriminant-Analysis-LDA-/main/Images/Dimensionality_Reduction_1.jpg)

# What is Dimensionality Reduction

The  techniques  of  dimensionality  reduction  are  important  in  applications  of  Machine Learning,  Data  Mining,  Bioinformatics,  and  Information  Retrieval.  The  main  agenda  is  to remove the redundant features by modifying the dataset to a lower-dimensional space.

In  simple  terms,  they  reduce  the  dimensions  (i.e.,  variables)  in  a  particular  dataset  while retaining most of the data. Multi-dimensional data comprises multiple features correlating with  one  another.  You  can  plot  multi-dimensional  data  in  just  2  or  3  dimensions  with dimensionality reduction.

# Working of Discriminant Analysis

The Linear Discriminant Analysis tries to project the features in higher dimension space onto a lower-dimensional space. This can be achieved in the following three steps:

- At  the  initial  step,  we  calculate  the ‘separability’ between  the  classes  (between-class variance).  It  is  estimated  as  the  distance  between  the  mean  of  different  classes.  This separability is kept in a between-class scatter matrix.

 
![](https://raw.githubusercontent.com/kasturi-sahu/Linear-Discriminant-Analysis-LDA-/main/Images/1_P3v__lMxUg_SOI7EbC7YVg.png)



- Compute the within-class variance or the distance between the mean and the sample of every class. This is another factor in the difficulty of separation —higher variance within a class makes a clean separation more difficult.


![](https://raw.githubusercontent.com/kasturi-sahu/Linear-Discriminant-Analysis-LDA-/main/Images/1_Cp1wdbPanOo4WoVhgupX6A.png)


- Construct   a   lower-dimensional   space   that maximizes the between-class   variance(‘separability’) and minimizes the within-class  variance.  It  is  also  known  as Fisher’s Criterion.    Linear    Discriminant    Analysis can    be    computed    using    singular    value decomposition, eigenvalues, or using the least-squares method.


![](https://raw.githubusercontent.com/kasturi-sahu/Linear-Discriminant-Analysis-LDA-/main/Images/1_20210304_162905_0000.png)


Let's take a look at LDA in action! Consider a very noisy two-dimensional scatter plot with two classes,  projected  by  LDA  into  one  dimension.  The  separation  is  much clearer  and  more distinct

![](https://raw.githubusercontent.com/kasturi-sahu/Linear-Discriminant-Analysis-LDA-/main/Images/Before-LDA-and-after-LDA_.jpg)

# Extensions & Variations

Due to its simplicity and ease of use, Linear Discriminant Analysis has seen many extensions and variations. These have all been designed to improve the efficacy of Linear Discriminant Analysis examples. 

Here are some common Linear Discriminant Analysis examples where extensions have been made.

- **Flexible Discriminant Analysis (FDA):**
Regular Linear Discriminant Analysis uses only linear combinations of inputs. The Flexible Discriminant Analysis all ows for non-linear combinations of inputs like splines.

- **QuadraticDiscriminantAnalysis(QDA):**
In Quadratic Discriminant Analysis, each classuses its own estimate of variance when there is a single input variable. In the case of multiple input variables, each classuses its own estimate of covariance.

- **RegularizedDiscriminantAnalysis(RDA):**
This method moderates the influence of different variables on the Linear Discriminant Analysis. It does so by regularizing the estimate of variance / covariance.

# Applications of LDA

LDA  can  be  used  in  various  applications  as  long  asa  problem  can  be  transformed  into  a classification  problem.  For  example,  LDA  can  be  used  as  a  classification  task  for  speech recognition, microarray data classification, face recognition, etc

# Additional Resources

[Linear Discriminant Analysis](http://https://sebastianraschka.com/Articles/2014_python_lda.html "Linear Discriminant Analysis")

[Linear discriminant analysis: A detailed tutorial](http://https://www.researchgate.net/publication/316994943_Linear_discriminant_analysis_A_detailed_tutorial "Linear discriminant analysis: A detailed tutorial")

[Classification in Python | logistic regression, LDA, QDA](http://https://www.youtube.com/watch?v=AKM1x237a3c "Classification in Python | logistic regression, LDA, QDA")

[LDA (Linear Discriminant Analysis) In Python ](http://https://www.youtube.com/watch?v=9IDXYHhAfGA "LDA (Linear Discriminant Analysis) In Python ")





[========]

# Notes 

![](https://raw.githubusercontent.com/kasturi-sahu/Linear-Discriminant-Analysis-LDA-/main/Images/1.jpg)

![](https://raw.githubusercontent.com/kasturi-sahu/Linear-Discriminant-Analysis-LDA-/main/Images/2.jpg)

![](https://raw.githubusercontent.com/kasturi-sahu/Linear-Discriminant-Analysis-LDA-/main/Images/3.jpg)

![](https://raw.githubusercontent.com/kasturi-sahu/Linear-Discriminant-Analysis-LDA-/main/Images/4.jpg)



