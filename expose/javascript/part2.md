1. What will happen at line 12 and why? If the code causes an error, explain why.
   Line 12 prints: 3
   Because the variable i is declared as a var variable which is function scoped, line 12 can still access i afte the for loop ends. When the for loop ends, i actually stores 3 because i was incremented to 3 after the last iteration.

2. What will happen at line 13 and why? If the code causes an error, explain why.
   Line 13 prints: 150
   Line 13 will print the last value that discountedPrice was assigned in the last iteration of the for loop because discountedPrice is a var variable which is function scoped, meaning it is accessible outside the for loop.

3. What will happen at line 14 and why? If the code causes an error, explain why.
   Line 14 prints: 150
   Line 14 will print the last value that finalPrice was assigned in the last iteration of the for loop because finalPrice is a var variable which is function scoped, meaning it is accessible outside the for loop.

4. What will this function return? Give a brief explanation why. If the code causes an error, explain why.
   This function will return discounted, the list of calculated discounted prices because each calculated discounted price gets pushed to the list and the list is accessible anywhere inside the function since it's a var variable.

5. What will happen at line 12 and why?  If the code causes an error, explain why. ^^^ (assume this function is being called like the others: discountPrices([100, 200, 300], 0.5)).
   Line 12 will throw an error because i is a let variable which is block scoped, meaning line 12 can't access the variable i outside the for loop where i is declared.

6. What will happen at line 13 and why? If the code causes an error, explain why.
   Line 13 will throw an error because discountedPrice is a let variable which is block scoped, meaning line 13 can't access the variable discountedPrice outside the for loop where discountedPrice is declared.

7. What will happen at line 14 and why? If the code causes an error, explain why.
   Line 14 prints: 150
   Line 14 will print the last value that's assigned to finalPrice because finalPrice is declared under the function block which means it is accessible anywhere inside the fufnction.

8. What will this function return? Give a brief explanation. If the code causes an error, explain why.
   This function will correctly return the calculated discounted prices list as expected without errors. discounted is a let variable and declared under the function so it is accessible anywhere inside the function, which means it will correctly get updated and returned as expected.

9. What will happen at line 11 and why? If the code causes an error, explain why.
    Line 11 will throw an error because i is declared as a let variable inside the for loop block, which means i is not accessible outside the loop.

10. What will happen at line 12 and why? If the code causes an error, explain why.
    Line 12 prints: 3
    Line 12 will print the length of the parameter list because length is declared with const in the function scope, which makes it accessible throughout the function.

11. What will this function return? Give a brief explanation. If the code causes an error, explain why.
    This function will return the calculated discounted prices list as expected because the variables are cleanly scoped and no errors will occur throughout the function. Plus, pushing values to discounted is fine as long as we're not reassigning it.

12. Given the above Object, write the notation for:  (These should be in your part2.md)
A. Accessing the value of the name property in the student object
student.name

B. Accessing the value of the Grad Year property in the student object
student['Grad Year']

C. Calling the function for the greeting property in the student object
student.greeting()

D. Accessing the name property of the object in the Favorite Teacher property in student
student['Favorite Teacher'].name

E. Access index zero in the array of the courseLoad property of the student object
student.courseLoad[0]

13. Arithmetic
A. '3' + 2: 32 since integers map to their exact string representation
B. '3' - 2: 1 because - converts 3 to a number
C. 3 + null: 3 because null maps to 0
D. '3' + null: 3null because it works like a string concatenation
E. true + 3: 4 because true maps to 1
F. false + null: 0 because false and null both map to 0
G. '3' + undefined: 3undefined because it works like a string concatenation
H. '3' - undefined: NaN because undefined maps to NaN

14. Comparison
A. '2' > 1: true because '2' maps to 2
B. '2' < '12': false because '2' > '1' in terms of string comparison
C. 2 == '2': true because '2' maps to 2
D. 2 === '2': false because 2 and '2' are different data types
E. true == 2: false because true == 1
F. true === Boolean(2): true because both sides are true

15. Explain the difference between the == and === operators.
    == compares values
    === compares both values and data types