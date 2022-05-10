# Bike-Buyers-Analysis-Excel

Company is trying to create an ad campaign to target the customers who are
the most likely to buy a bike as well to promote the importance of using
bike as transportation to the ones who are less likely to be the customers.


Main task
Create dynamic dashboard that answers following questions:

Questions to answer
1)Average income of people who bought a bike or not?
2)Does the commuting distance affects customers decision to buy a bike?
3)Does age plays a role in customers decision to buy a bike? 


Dataset includes demographic of the people who bought a bike and the ones who did not. 

Steps performed
Cleaning data
-Finding duplicates
-Reformating columns
-Performing IF statement for column M 
(IF(L18>54,"Old",IF(L4>31,"Middle Age",IF(L4<31,"Adolescent","Invalid"))

Creating Pivot Table

1)Insight shows the average salary of male and female followed by 
side by side column chart

2)Spaghetti chart has been created to show the relations between 
male and female where it indicates the commuting distance in miles and how the
distance affects decision making if to buy or not.
(Spaghetti chart is adequate here although I would avoid using it for
more than two factors involved, in fact any kind of "food charts" so to say :D )

3)Using previously filtered M column to create age groups we can indicate
to what extent age represents a factor and which group is the most likely to buy a bike.
Overlaping male/female line chart is created that clearly states that customers considered to be Middle Aged between 31 and 54 years are the ones 
representing majority of customers who bought the bike. 

4)Dynamic dashboard has been created by using slicers that filter out Marital Status, Region & Ocupation.

Overall conclusion
Middle Age customers are the ones the most interested to buy a bike. They can be used as a focused group to target in order to increase sales and profit.
Adolescent group(particualry females) are the least likely to buy a bike. They should be targeted as a focused group to raise awareness.
