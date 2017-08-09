Problem 1:
  a)Divide into groups of 3
    Compare two groups of 11 that gives you the group of 11 with the fake either by comparison on the scale or by excluding it from 
    the scale.
    Split into 3 groups again 3 3 4 and compare them.
    Again split into groups of either 2 and 2 or 1 1 1 and worst case 
    Repeat again for 1 v 1 and you have the fake. 
  B) The basic idea of splitting into three groups works for all cases just splitting into either 3 equal or 2 equal and one odd
     one out. Either way you eliminate the majority of groups each time. 
     ends up worst case with [Log2(N)] - 2

Problem 2:
  A) To solve problem 2 in 4 multiplications and 3 additions, you need to split each six digit number into two groups of 3
    You will end up with 2 sets of 3 leading digits and 2 sets of 3 end digits. 
    To find the answer you multiply the leading digits and multiply it by 10^6
    Multiply the end digits
    Multiply the first numbers leading digits and the last numbers end digits, multiply by 10^3
    Multiply the second numbers leading digits and the first numbers end digits and multiply it by 10^3
    Add them sequentially in 3 additions and that gives you an answer

    
 
