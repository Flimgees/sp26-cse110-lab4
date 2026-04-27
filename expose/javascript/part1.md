1. Line 9 prints the added results of parameters num1 and num2 if and only if the add parameter is true.
2. Line 13 will print the sum of parameters num1 and num2 if add is true.
3. You should not use var because the variable will be in function scope, meaning it will be accessible throughout the whole function no matter if it is placed in an if block that may be skipped. Defining it within the function scope makes the variable more prone to naming conflicts and scoping issues.
4. Line 9 will also return the sum of num1 and num2 if add is true.
5. Line 13 will return an error in this situation because the let declaration is block scope, so it will only be initialized in the if block. Since result is initialized is not initialized outside the if block, it cannot print the resulting number, so it returns an error.
6. Line 9 will print an error since the code is ttrying to change the value of a constant.
7. Line 13 will print the same error as question 5 as the const declariation is block scope, so it will not initialize outside the if block, so line 13 will return an error.
