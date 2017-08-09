Problem 1:
  a)Fake among 33 Coins
    Remove 1 coin (if two groups of 16 are equal, the fake is the extra coin, if not it is a real coin)
    Split into two groups of 16
    Determine which group has the fake
    Split again into 8
    Repeat
    Split in 4's
    Repeat
    Split in 2's
    Repeat
    Finally 
    Compare last two 
    Find the fake
  B) For N>=1 coins you can repeat the same process, divide into two groups and seperate the odd man out when the total is an odd #
    Requires log2(N) comparisons

  
