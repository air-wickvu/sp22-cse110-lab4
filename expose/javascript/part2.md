1. print 3
2. print 150
3. print 150 
4. return: 50, 100, 150; The for loop iterates through the `prices` array and executes the calculations within the loop. The final calculations for each index are stored in the `discounted` array which is the array returned. 
5. The code causes an error because the variable `i` is declared with `let` and is block scoped. Therefore, it is not accessible outside the for loop. 
6. The code causes an error because `discountedPrice` is declared with `let` and is block scoped. Therefore, it is not accessible outside the for loop. 
7. print 150; Line 14 will print 150 because the `finalPrice` variable is declared with `let` within the same block as the print statement. 
8. print 50, 100, 150; The for loop iterates through the `prices` array and executes the calculations within the loop. The final calculations for each index are stored in the `discounted` array which is the array returned. Since `discounted` was declared with `let` within the same block as the print statement, it is accessible and will print the values. 
9. The code causes an error because the variable `i` is declared with `let` and is block scoped. Therefore, it is not accessible outside the for loop. 
10. Line 12 will print 3 which is the length of the `prices` array.
11. return the `discounted` array storing the values: 50, 100, 150. You are still able to change the elements of a const array, but you cannot reassign the array itself. 
12.
    - A. `student.name`
    - B. `student['Grad Year']`
    - C. `student.greeting()`
    - D. `student['Favorite Teacher'].name`
    - E. `student.courseLoad[0]`
13. Arithmetic 
    - A. `string: 32`; because the `+` operator is used for both arithmetic and concatenation, the `+` operator will concatenate the two strings.
    - B. `number: 1`; because the `-` operator is used for arithmetic. Javascript will convert `3` to a number and subtract `2` from it. 
    - C. `number: 3`; because the `+` operator is used for arithmetic. Javascript converts null to `0` and adds `3` to it.
    - D. `string: 3null`; because the `+` operator is used for concatenation. `3` is a string and concatenates it with `null`.
    - E. `number: 4`; because the `+` operator is used for arithmetic. Javascript converts `true` to `1` and adds `3` to it.
    - F. `number: 0`; because the `+` operator is used for arithmetic. Javascript converts `false` and `null` to `0` and sums it. 
    - G. `string: 3undefined`; because the `+` operator is used for concatenation. `3` is a string and concatenates it with `undefined`.
    - H. `number: NaN`; because the `-` operator is used for arithmetic. Javascript converts `undefined` to `NaN` and `undefined` cannot be converted to a number. 
14. Comparison
    - A. `true`; because the `>` operator is used for comparison. Javascript coerces the string to a number and compares the two numbers. 
    - B. `false`; because the `<` operator is used for comparison. The comparison operator compares the strings character by charactter, and since 2 is greater than 1, the result is false. 
    - C. `true`; because the `==` operator is used for comparison. Javascript coerces the string to a number and compares the two numbers.
    - D. `false`; because the `===` operator is used for comparison. Javascript does not coerce the string to a number and compares the two values. Since the two values are not the same type, the result is false. 
    - E. `false`; because the `==` operator is used for comparison. Javascript coerces the boolean to a number and compares the two numbers and 0 does not equal 2 so the result is false. 
    - F. `true`; because the `===` operator is used for comparison. Boolean converts the 2 to true and since the two values are the same type and value, the result is true. 

15. The difference between the `==` and `===` operators is that the `==` operator coerces the values to the same type and then compares the values. The `===` operator does not coerce the values to the same type and compares the values.

16. `part2-question16.js`
17. 


