1. What is printed by line 9?  Line 9 will print `values added:  20` <br>
   
2. What is printed by line 13?  Line 13 will print `final result:  20` <br> 
   
3. What is printed by line 9?   Line 9 will print `values added:  20` <br> 
   
4. What is printed by line 13?  The code returns a referenceError: result is not defined. We get this error because the `let result` variable is declared within the `if` block which means it can only be accessed within that block. Outside of the `if` block `result` is not accessible. Therefore, attempting to access `result` on line 13 will result in a Reference Error becasue `result` is not defined in that scope.<br>
   
5. What is printed by line 9? The code returns a TypeError: Assignment to constant variable. we get this error because we are reassign a new value to a constant `result`. On line 7 we reassign `result` with new value `num1 + num2`. Therefore attempting to assign a new value to `result` will result in a TypeError. <br>
   
6. What is printed by line 13? The code returns an error as well because the error occurs before line 13 is reached, it won't execute. The error happen on line 7 when we reassign `result` with new value `num1 + num2`. Therefore, line 13 will not reached and the code will not print anything beyond the error message.
