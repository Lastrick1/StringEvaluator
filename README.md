# StringEvaluator

Evaluates arithmetic string to value (or error). Initially handles +, -, *, division and parentheses. 

****************************** Example CODE ****************************

import streval as s

myString = input("Enter string to evaluate: ")

print(myString + " => " + s.evaluateStr(myString))

RESULT: 

Enter string to evaluate:  (2 + (8 / 4) * 5) - 2

(2 + (8 / 4) * 5) - 2 => 10.0
