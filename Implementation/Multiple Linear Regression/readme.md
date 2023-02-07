First Let us understand the data for which we are going to make a model.
![Data in github photo](https://user-images.githubusercontent.com/104156901/217296786-085e0289-90b5-4f90-8f7e-0291bd9391cd.png)

As the Data has 4 features in which we are going to predict the **antibodies**.
**age**:- The person's age.
**Body Temperature**:- Here we have 2 categories( High,Moderate).
**Chronical Disease**:- This feature or column says that the person has how many diseases like fever, heart disease, cancer, diabetes e.t.c .
**Blood O2 level in percentage** :- It says that the person oxygen level in percentage.

Finally we need to find the **antibodies** based on above features.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Here when we observe the above independent variables , that **Body Temperature** has categorical features so we need to change them into **1's** and **0's**. 
We need to trap dummy feature because the featurs for high and moderate will depend (high+moderate=1) So we need to ensure that one feature must be trapped.
- - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - - 
Finally the accuracy we got for this model is **0.9757884356345478**
