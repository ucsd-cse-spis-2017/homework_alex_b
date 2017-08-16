1. To find the smallest set of coins, divide the amount of n cents by 8 and that is the number of octels you use.
    then divide the remainder by five and that will give you the number of nickels you use, either 1 or 0, then use pennies to fill the rest of the coinset.
    2. Moving only up or left, start from the bottom right, compare the cost of the two paths you could take. Move to the path of least resistance, if they are equal, both could be taken. Continue this process for each intersection until you reach the top. If you have multiple paths, compare their cost and choose the smallest one.
3. 
