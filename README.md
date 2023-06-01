# Arithmetic-arranger.py
Scientific Computing with Python Projects (FreeCodeCamp certification)

As I mentioned this is part of Scientific Computing with Python Projects (FreeCodeCamp certification),
https://www.freecodecamp.org/learn/scientific-computing-with-python/scientific-computing-with-python-projects/arithmetic-formatter

My job was to create a function that receives a list of strings that are arithmetic problems and returns the problems arranged vertically and side-by-side. 
The function should optionally take a second argument.
When the second argument is set to True, the answers should be displayed.

Example:

Function call:

arithmetic_arranger(["32 + 698", "3801 - 2", "45 + 43", "123 + 49"])

Output:

   32      3801      45      123
+ 698    -    2    + 43    +  49
-----    ------    ----    -----

Function call:

arithmetic_arranger(["32 + 8", "1 - 3801", "9999 + 9999", "523 - 49"], True)

Output:

 32         1      9999      523
+  8    - 3801    + 9999    -  49
----    ------    ------    -----
  40     -3800     19998      474
  
The files main.py and test_module.py were already assigned and the TODO section was located in arithmetic_arrange.py
To solve this task, I used the regular expression library, with the help of which I solved the character problem, because the task only requires "+" and "-" operations.
