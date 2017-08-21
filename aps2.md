1. To find the absolute smallest number of coins, you must use a recursive function. First, use as many octels as you can, and compare that number of coins to a set of coins with max number of (octels-1), and use as many nickels as possible to split the sum and continue it recursively.
    2. Make a grid of coordinates and start and end points, calculate single step costs first and continue to build up the list working your way down towards the bottom right, using previously calculated routes to provide information to reduce the number of operations along the way.
3. 
