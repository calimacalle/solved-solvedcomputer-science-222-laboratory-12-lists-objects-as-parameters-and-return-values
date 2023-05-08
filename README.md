Download Link: https://assignmentchef.com/product/solved-solvedcomputer-science-222-laboratory-12-lists-objects-as-parameters-and-return-values
<br>
Learningobjectives:

Implement a built-in Python list function.

Develop a class with object parameters and return types.

Use a driver program to test the class.

Gettingstarted: Download testMoney.py.

1.Writing our own reverse.

Write your ownversion of reverse. The real reverse is a method of the List class inPython, and we are not allowed to add new methods to a built-in class, so our reverse will be a function. Put it in the file reverse.py.

Write reverse(&lt;list) so that the values in Note that reverse does not return anything.That is, there is not a second list.The one and only list has its values reversed in place. reverse() must not use a break or a continue, and must have no return. Write amain() that makes a couple of callsto reverse().

Demonstrate forthe instructor.

2. AMoney Class

Define a class named Moneywhose objects represent amounts in U. S. money, and put it in the file money.py.The class must have two instance variables of type int for the dollarsand cents parts of the amount of money. Donot use any float variables or values in this program.

Write a constructor that setsdollars and cents to zero. Write getter methods for the dollars and the cents.At this point all that testMoney does is create a Money object and print its values.

Demonstrate for the instructor.

3.Setters

Write setter methods for the dollarsand the cents. The setters must ensure that only non-negative values arestored. If a user enters a negative amount, keep the current value. Make sureto always maintain a “correct” number of dollars and cents at all times. Thatis, you should never store something like 1 dollar and 115 cents; the correctrepresentation is 2 dollars and 15 cents.

Uncomment so that testMoneytests the setters. Demonstrate for the instructor.

3. __str__()Method

Write a __str__ method that returns a string containing a dollar sign, the dollaramount, a decimal point, and the cents amount as two digits (regardless of its value). Don’t return or printanything else!

Uncomment so that testMoneytests the __str__ method. Demonstrate for theinstructor.

4. increment()Method

Write a method, increment(m), that adds to the amount in self the amount in the parameter m, which is a Money object.So if m1 holds 2 dollars 90 cents and m2 holds 1 dollar 20cents, the call m1.increment(m2) changes the amount in m1 to 4dollars 10 cents. No value is returnedby this method.

Uncomment so that testMoneytests the increment() method. Note that increment() uses only two objects, the caller (which becomes self) and the argument. Demonstrate for the instructor.

5. add() Method

Write a method, add(m),that adds the amount in self and theamount in the parameter and returnsa new Money object. So if m1 holds 2 dollars 90 cents and m2 holds 1 dollar 20cents, the call m3 =m1.add(m2) returnsa third Money object m3 with avalue of 4 dollars 10 cents.

Uncomment so that testMoneytests the add() method. Note that add() uses three objects, the caller (which becomes self), the argument, and a new Money object. Be sure to test fully.Demonstrate for the instructor.

Uploadthe files (don’t forget to submit):

reverse.py ______ Money.py ______

Thanks for all your work in lab this semester!