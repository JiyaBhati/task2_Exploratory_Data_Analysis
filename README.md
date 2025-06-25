 Task2 : Exploratory_Data_Analysis (EDA)

 Its crucial to understand the patterns and know your data before you actually start working on it ,  hence EDA is used. 

 First ,  i imported the libraies ,  imported the dataset to work on. 
 To understand the structure and details of the dataset i used .head() , .shape  

  Step1 :  I performed Summary Statistics on  ---
  the numerical columns

  then on all the columns :  including objects 

  and lastly on just objects 

  additionally  , i performed summary statistics such  as mean ,  median for indivial columns for a clear pattern. 

  Step 2 : i created histogram , distplot and boxplot for identifying the distribution , the skewness and the possible outliers.

  step 3 : i used pairplot and correlation matrix for feature relationship 
   performed countplot to get the relation between survival rate relation with other atributes. 

 Key Observations : 
 Age group 20-25 were the most in numbers.
 Most people didnt survive, 549 died and 342 survived.
 for 'Fare' the calculated maximum is around 65 and all the values above that are considered as potential outliers by boxplot.
 Passanges with class 1 had a higher rate of survival.
 Higher fares had a higher rate of survival.
 More people travelled on 3rd class.
 More number of males were traveling.
 Women had a higher rate of survival.
 Children had a higher rate of survival.
 61.62% died and only 38.38 % survived.
 Possible Outliers were visible in the columns 'Age' and 'Fare' , on looking at the column ' Cabin ' which has a lot of missing values , it becomes inconsitent to be working with and is a an anomaly.
 By performing EDA on the Titanic dataset we can say the survival rate were mainly affected by these factors : Pclass , Sex , Age and Fare. 

 Dataset used  : Titanic Dataset 
 Link to the dataset : 
 
