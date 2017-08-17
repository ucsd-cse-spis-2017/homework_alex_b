1. If N>35 To find the smallest set of coins, divide the amount of n cents by 8 and that is the number of octels you use.
    then divide the remainder by five and that will give you the number of nickels you use, either 1 or 0, then use pennies to fill the rest of the coinset.
    if N<35
        Check if it is a multiple of 5 or 8:
            If it is a multiple of either then use only those coins
            else
            
     if n<8
        use 1 nickel + combo of pennies
     if n<5
        use only pennies
    2. Moving only up or left, start from the bottom right, compare the cost of the two paths you could take. Move to the path of least resistance, if they are equal, both could be taken. Continue this process for each intersection until you reach the top. If you have multiple paths, compare their cost and choose the smallest one.
3. 
