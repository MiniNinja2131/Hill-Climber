## Hill Climbing Genetic Algorithm

**Background:** Hill climber may be used to find solutions to a wide variety of problems. Each 
hill climbing individual  increases its fitness through trial and error e.g., 
 
1. Create a random individual 
2. Change (mutate) the individual  
3. Measure fitness. If it is worse then keep original  
4. Go to 1

We will implement a population of such hill climber all evolving independently. The problem is 
as follows: 

The knapsack (KP) problem is an example 
of a combinatorial optimization problem. It is 
concerned with a knapsack that has positive 
integer volume (or capacity) **V**. There are **n** 
distinct items that may potentially be placed 
in the knapsack. Item **i** has a positive integer 
volume **Vi** and positive integer benefit **Bi**. In 
the most basic form of the problem we will 
consider there are only one of each item 
available (0-1 KP).

### Explanation
For example suppose we have a knapsack that has a capacity of 20 cubic inches and N=10 
items of different sizes and different benefits. We want to include in the knapsack only these 
items that will have the greatest total benefit within the constraint of the knapsack’s capacity. As seen in the table below: 

![Item available for knapsack problem](https://github.com/MiniNinja2131/Hill-Climber/blob/master/itemBagTable.PNG)
