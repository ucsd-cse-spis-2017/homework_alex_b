

    (20 pts) Guttag discusses variables and names at some length on pages 12 and 13 (section 2.1.2) What are the four most important points that you would take away from this section?
    1. Variable names are just assignments of names to values
    2. Variable names can be extremely important in readability of code.
    3. Variable names cannot be reserved words/keywords because they are already predefined in python's ruleset.
    4. Comments also improve readability of the code.

    (20 pts) In Python, indentation and nesting are signficant concepts. Guttag offers an explanation of these, with some examples. If you feel like you understand these from his explanation, my question is: how would YOU explain these concepts to someone new to the Python language? That is: use your own words, not Guttag’s. If you feel like your understanding is still not firm, what questions would you ask about indentation and nesting, after reading Guttag’s explanation?
    Organization of code similar to how someone would organize their notes, with indents and nesting are crucial to the execution and meaning of what you type. While in practice for writing it solely improves readability, in python nesting and indents change the meaning of your code based on how it is arranged. It adds another element to python syntax. 
    (20 pts) Suppose you want a Python program to ask the user a question (e.g. “What is your name”?) and store the answer in a variable called “users_name”. How do you do that?
    user_name = input("What is your name? ")

    (30 pts) Guttag discusses iteration in Section 2.4. A while loop continues while its condition is true, and ends when its condition is false. If it’s condition is false the first time it is encountered, the body of the loop is never even executed once.
    
    These leaves us with three possibilities:
        A while loop that is never executed
        A while loop that will be executed a finite number of times (e.g. 3)
        A while loop that will never terminate (a so-called “infinite loop”)

    Write an example of each of these kinds of while loops in Python. Try them in IDLE and see what happens.
    Never Executed: While true == false:
    Finite: While Count < 3
      

    (10 pts) Try the first “finger exercise” on p. 24.
