1. What will happen at line 12 and why?  This line log the value of the variable `i` to the console.
2. What will happen at line 13 and why?  This line outputs the function definition to the console which means that the console will display the textual form of the `discountPrtices` function itself.
3. What will happen at line 14 and why? Line 14 logs `150` to the console. This is because it is the final computed and rounded discounted price from the last iteration of the loop.
4. What will this function return? Give a brief explanation why. The `discountPrices` function returns an array `[50.00, 100.00, 150,00]` for input `[100, 200, 300]` with a discount rate of `0.5` because it calculates the discounted price of each item by halving it(due to the 50% discount), then rounding to two decimal places, and adds each result to an output array.
5. What will happen at line 12 and why? This line returns a ReferenceError: i is not defined. This error is due to the variable `i` being declared with `let` within the `for` loop. This means that a variable declared `let` in a block is only accessible within that block so in here variable `i` goes out of scope making it inaccessible to any code outside the loop block.
6. What will happen at line 13 and why? This line returns a ReferenceError: discountedPrice is not defined. This error occurs because the variable `discountedPrice` is declared with `let` within the `for` loop which means it has block scope, so it is not accessible outside of that loop block. Attempting to access it after the loop results in it being undefined in that context.
7. What will happen at line 14 and why? This line 14 will successfully execute without any errors because the variable `finalPrice` is declared with `let` at the beginning of the function, not inside the `for` loop. This placement makes `finalPrice` accessible throughout the entire function.
8. What will this function return? The `discountPrices` function returns an array `[50.00, 100.00, 150,00]` for input `[100, 200, 300]` with a discount rate of `0.5` because it calculates the discounted price of each item by halving it(due to the 50% discount), then rounding to two decimal places, and adds each result to an output array.
9. What will happen at line 11 and why? This line causes a ReferenceError: i is not define. The error occurs due to the scope of the variable `i` which is declared with `let` within the `for` loop. This means it can only be accessed within the block of the loop where it was declared. Attempting to access `i` outside of its declaration block will result in a `ReferenceError` because `i` does not exist in the scope where `console.log(i); is called.<br>
10. What will happen at line 12 and why? The statement `console.log(length);` will successfully execute and log the value of `length` to the console because `length` is declared with `const` outside the `for` loop, making it accessible throughout the entire function. Its value is set to the number of items in the `prices` array and remains unchanged.<br>
11. What will this function return? Give a brief explanation. The function `discountPrice` will return the array `[50, 100, 150]` when called with the input `[100, 200, 300]` and a discount of `0.5` this function calculates the discounted price for each item in the `prices` array by multiplying each item by `(1 - discount)` given a discount of `0.5` this calculation halves each price then each discounted price is added to the array `discounted` which is returned at the end of the function.<br>
12. Given the above Object, write the notation for:<br>
A. Accessing the value of the name property in the student object: `student.name`<br>
B. Accessing the value of the Grad Year property in the student object: `student['Grad Year']`<br>
C. Calling the function for the greeting property in the student object: `student.greeting();`
D. Accessing the name property of the object in the Favorite Teacher property in student:  `student['Favorite Teacher'].name`<br>
E. Access index zero in the array of the courseLoad property of the student object: `student.courseLoad[0]`<br>
13. Arithmetic <br>
A. '3' + 2 <br> **output:** `32` when we have `+` operator with a string the integer is converted into a string so in this case The number 2 is automatically converted into a string and appended to the string`'3'` which results in  `'32'`.<br>
B. '3' - 2 <br> **output:** `1` when we have subtraction with string the string is converted into interger so in this case string 3 converts to number 3 and then 2 is subtracted which results in `1`.<br>
C. 3 + null <br> **output:** `3` since null convert to 0 so 3 + 0 gives `3`<br>
D. '3' + null <br> **output:** `3null` since null is converted to string and concatenated with `'3'` <br>
E. true + 3 <br> **output:** `4` since true map to 1, so 1 + 3 gives `4`<br>
F. false + null <br> **output:** `0` since false map to 0, so 0 + 0 gives `0`<br>
G. '3' + undefined <br> **output:** `3undefined` since undefined map to the string then it concatinate with string 3. 
H. '3' - undefined <br> **output:** `NaN` since undefined map to Nan and any operation with `NaN` result in `NaN`.<br><br>
14. Comparison <br>
A. '2' > 1 <br> **output:** `true` comparison operators return a boolean value, and in this case 2 converted to the number 2 then compare it to 1 which result in `true` because 2 is greater than 1.<br>
B. '2' < '12' <br> **output:** `false` since '2' comes after '1' in lexicographical order thus, '2' is considered greater than '12' we got false.<br>
C. 2 == '2' <br> **output:**  `true` since '2' converted to the number 2 so 2 is equal to 2.<br>
D. 2 === '2' <br> **output:** `false` since no type conversion occurs we got false.<br>
E. true == 2 <br> **output:**  `false` since true map to 1 and 1 is not equal to 2. <br>
F. true === Boolean(2) <br> **output:** `true` since both operands are type boolean they are considered strictly equal. <br><br>
15. Explain the difference between the == and === operators. <br> **Answer:** The `==` means (equality operator) checks for equality after performing type conversion if the types are different. On the other hand the `===` means(strict equality operator) checks for equality without performing type conversion if types are different, and if types are different it outputs false.
