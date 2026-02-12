
SmartListf filter and Rebuilder is implemented in python

GOAL 
 create a python program that filters a mixed list into numbers and strings,applies a personalized logic rule,and displays counts and results
 LOGIC :
  Use a for loop to chech each element
  Numbers -> added to number numberlist using int condition 
  Strings->  added to string list using str condition
  Empty strings are ignored.


Personalization Rule(Name logic)
  Name length logic :
        Even length -> remove first element from both lists
        odd length ->  remove the last element from both lists

Counters 
 total_numbers -> counts numbers
 tottal_strings -> counts strings

Output
 Displays numbers list
 Displays strings list
 Final output changes based on personlization logic
