# Answers for Part 2

1. Line 12 prints the value 3 because "i" is declared as a var which means that the variable can be accessed outside the block. Once the for loop is ran, i ends off with the value of 3 because the size of prices is 3.
2. Line 13 prints the value 150 because it will take the discount price of the last element in the array since "discountedPrice" is updated after each iteration. When you apply the discount to 300, it comes to 150.
3. Line 14 prints the value 150 because the last update to "finalPrice" would be 150 * 100 / 100 which is 150.
4. The function returns [50, 100, 150] because the loop takes the discount of each item in the list and pushes it to a new list which is what gets returned.
5. When it comes to printing line 12, there was an error because "i" was declared with "let" which makes it a local variable, so when you try to call the variable from outside its scope, an error will be thrown when you try running it because it wasn't defined properly. You can only call the variable within the for loop.
6. When it comes to printing line 13, there  was an error because "discountedPrice" was declared with "let" which means that it can only be used within the scope it was declared which is the for loop. If you try calling the variable outside the scope, you get the error that the variable was undefined.
7. Line 14 prints out 150. There is no error here because the declaration of "finalPrice" is in the same scope as when finalPrice was called to print. The scope here would be the function meaning that the variable will print properly.
8. The function would return [50, 100, 150]. Since the variable "discounted" was declared with the "let" keyword, then discounted can only be used within the specific scope which is the function. The variable "discounted" is just the variable "prices" but each item in the list is multiplied by half which is what the value of the "discount" variable is.
9. When it comes to printing line 11, there was an error because "i" was declared with "let" which makes it a local variable, so when you try to call the variable from outside its scope, an error will be thrown when you try running it because it wasn't defined properly. You can only call the variable within the for loop.
10. Line 12 prints out 3 because the variable "length" was declared earlier in the function and was never reassigned because it was a const variable. Since it is declared in the same scope, there is no error in calling it.
11. The function returns [50, 100, 150]. Even though the list "discounted" changes after every iteration of the loop, there was never any reassignment of the variable which means that there should not be an error.
12.  
     * To access the name of the student object, you would use student.name
     * To access the Grad Year of the student object, you would use student["Grad Year"]
     * To call the greeting function for the student object, you would use student.greeting()
     * To access the name of the student's favorite teacher, you would use student["Favorite Teacher"].name
     * To access the first element in the student's "courseLoad", you would use student.courseLoad[0]
   
13. 
    * The output of  "3" + 2 is 32 because javascript reads this as a string concatenation so it is the same as "3" + "2" which would be 32.
    * The output of "3" - 2 would be 1 because javascript reads this as numerical subtraction since you can't subtract strings from each other, so it converts it to 3 - 2 which is 1.
    * The output of 3 + null would be 3 because javascript reads the null as 0 when you are doing an addition to another number, so 3 + 0 = 3.
    * The output of "3" + null is 3null because javascript reads it as string concatenation since there are quotes being used which means it is equivalent to "3" + "null" which is 3null.
    * The output of true + 3 would be 4 because in javascript, true and false are read as binary numbers where 1 represents true and 0 represents false. This means javascript reads true + 3 as 1 + 3 which is 4.
    * The output of false + null would be 0 because javascript reads false as 0 when doing addition and reads null as 0 so the statement is equivalent to 0+0 which is 0.
    * The output of "3" + undefined would be 3undefined because javascript reads this as a string concatenation since quotes were being used in the beginning, so it is equivalent to "3" + "undefined" which is 3undefined.
    * The output of "3" - undefined would be NaN which means the value of the output would be undefined. This happens because javascript reads this as an equation since you cannot subtract from strings and when you add or subtract a number from any undefined value, it wil always be undefined. It is similar to 3 - 1/0 which is undefined. 

14. 
    * The output of '2' > 1 is true because javascript converts the string into a numeric value since it is comparing it to another number, so 2 > 1 would output true.
    * The output of '2' < '12' would be false because when comparing two strings, javascript compares the value from left to right so it first compares the 2 and the one and since 2 has a greater unicode value than 1, then the output would be false.
    * The output of 2 == '2' would be true since javascript can do an automatic type conversion so the string is converted to a number and 2 does in fact equal 2 so it would return true.
    * The output of 2 === '2' would be false because === is a more strict comparison than == so it compares the data types as well and since one type is an integer and the other is a string, the output would be false.
    * The output of true == 2 would be false because true gets converted to a numeric value which would be 1 and 1 does not equal 2.
    * The output of true === Boolean(2) would be true because 2 gets converted to a boolean and any non-zero value becomes true when it is converted to a boolean so it is similar to true === true which is true.
15. The difference between == and === is that === is a more strict comparison than == so === compares the data types as well as the value while == just compares the value being compared.
16. File is in the javascript folder labeled [part2-question16.js](https://github.com/hbaobaid00/sp24-cse110-lab4/blob/main/expose/javascript/part2-question16.js)
17. The result of the function call would be the list [2, 4, 6] because when we pass in the array in the function, it iterates through each element in the list and calls doSomething with the parameter of each element in the list. So every number in the list gets multiplied by 2 and gets pushed to a new array.
18.  
