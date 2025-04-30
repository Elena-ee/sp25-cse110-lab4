1. What is printed by line 9? If the code returns an error, explain why.
   values added: 20

2. What is printed by line 13? If the code returns an error, explain why.
   final result: 20

3. Why should you not use var? Explain why.
    var is function scoped which means it can be risky to use var especially when we have blocks like conditionals that does something to the variable if the condition is met.
    var variables can be easily overwritten without even being realized...

4. What is printed by line 9? If the code returns an error, explain why.
   values added: 20

5. What is printed by line 13? If the code returns an error, explain why.
   Line 13 returns an error because the variable is a let variable which has a block scope and it's declared within the if block. Line 13 is outside the if block which means the variable is not accessible.

6. What is printed by line 9? If the code returns an error, explain why.
   It can't reach line 9 because we will encounter an error at line 7 where it's trying to reassign a const variable.

7. What is printed by line 13? If the code returns an error, explain why.
   It would throw an error because the variable is not accessible outside the if block. But in this case, it wouldn't even reach line 13 because line 7 was trying to reassign the const variable which's not valid.