#ABSTRACT#:
According to the dataset considered, this situation deals with violation of laws and the features related to citations in court from different areas for different
people. Most of the times when there is violation of law, the authorities settle it using charges. Few times there are cases where people are charged without 
commiting any violations or there are cases where people resist the charges for a inevitable reason. so in this work, for a citation, we are going to find if the
hearing Status is issued or not meaning we are trying to understand how features of citations are affecting people who face any hearing status and people who don't 
have one. This helps us to know better about the current mindset of people and the mistakes made by them and in-turn provide a analysis for judistriction for easy 
flow of their work.

1.importing all the required libraries 
2.Data Acquisition process 
3.as the data is very large we are taking only data which we can handle i.e 50,000 rows
4.then i found out the number of unique rows in the given data which was noted to be 30.

later removing the columns which are insignificant

1.columns with large number of unique values
2.we are not performing time series analysis. so, removing the columns with time related data.i have done this by using an internal function called drop.

later, understanding all the different categorical column's with data distributions.
