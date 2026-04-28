1. Line 12 will print out the number of times the for loop occurs, which should be (prices.length -1).
2. Line 13 will print the discounted price of the final item in the price array. Since the variable is declared with var, it is within the function scope, meaning we can access the discountedPrice variable after the if code block is ran. Since it is iterating and applying the discount to the price of each item in the prices array, the discountedPrice variable will store the discounted price of the final item in the array before ending the loop and reaching line 13. Thus, printing the result above.
3. Line 14 will print out the prices array's final element's rounded discounted price. For each iteration in the for loop, the discounted price of each element is calculated in the discountedPrice variable. The finalPrice variable uses the math library's round function to round the discounted price and then store it in the finalPrice variable. Since we call line 14 outside of the if block, it will print out the final element's final price.
4. The function will return the discounted array, which contains the final discounted prices of each element from the parameter prices array. After each element's final price is assigned to variable finalPrice, it is pushed into the array "discounted". This array is within the function scope, so it is called upon after the for loop and retrieves the array contain ech element's final price.
5. Line 12 will throw an error because the let declaration of i is block scope, so after running the for loop where i is declared, it erases the initialization of it, so the computer cannot access any information on this variable and returns an error.
6. Line 13 will also throw an error for the same reason as question 5. discountedPrice is initiated inside the for block and has the let declaration, so when the loop ends and we print discountedPrice, we cannot access its contents and it returns an error.
7. Line 14 will print out the prices array's final element's rounded discounted price as the variable is declared outside of the loop. This means that when we go to print the variable, the computer can access its data freely and pirnt out the final element's discounted price.
8. When returning discounted, it will return an array of elements containing the elements price with their discounted prices. Since finalPrice and discounted are both initialized outside of the loop, we can refer to their final values throughout the whole function. Thus, the discounted array will contain the final price of every element within the original price parameter.
9. Line 11 will cause an error i is initialized with the let declamation which is in the scope of the for loop. Thus, when printing it, it will be referring to a variable that does not exist anymore.
10. Line 12 will print the length of the parameter prices. Since length is declared as a constant, it is block scoped outside of the loop which allows us to refer to the variable's value and return it with no problems.
11. The function will return the discounted prices of all elements within the prices array. Although discounted is declared as a const, the .push() function can still add values to the array without throwing an error since we are not reassigning the variable's value.
12.
    - A. student.name;
    - B. student['Grad Year'];
    - C. student.greeting();
    - D. student['Favorite Teacher'].name;
    - E. student.courseLoad[0];

13.
   - A. '32' JavaScript tells that you are adding a string to a number, so it changes the type of 2 to string and concatenates the two.
   - B. 1  Since you cannot subtract a number from a string, JavaScript changes the string type to numerical and outputs 1.
   - C. 3 Null is treated as a zero when doing arithmetic, so it returns 3.
   - D. '3null'  Null is treated as a string when doing addition with another string, giving us '3null'
   - E. 4 When doing arithmetic, true is treated as 1, so 3 + 1 = 4.
   - F. 0 Since false is equivalent to 0 as a number and null is also treated as 0, the result is 0.
   - G. '3undefined' Since '3' is a string, undefined is considered a string by JavaScript and outputs the concatenated string.
   -  H. NaN Subtraction tries to convert both sides into numbers, but undefined as a number is converted to NaN, leading the result to be NaN.

14.
    - A. true The string 2 becomes a numerical value, so 2 > 1 is true.
    - B. false
    - C. true
    - D. false
    - E. false
    - F. true

15. The == symbol stands for equality to check if two operands are equal. However, the == symbol tries to convert and compare operands if they are different types. The === stands for strict equality and it does not try to convert operands if they are different.

17. The function will return [2,4,6]. First, we start by initializing newArr and entering the for loop. The for loop calls the doSomething function for each iteration and multiples the parameter by two. For each iteration, the doubled element in the array parameter is pushed into the newArr, returning newArray that contains the doubled values of all elements in array.
19. 
   
