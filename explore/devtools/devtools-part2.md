What was the bug? <br>
The bug was that the + operator was concatenating num1 and num2 instead of adding them as numbers. which result in the output`32` instead of performing the artihmetic.<br>

How would you fix it? <br>

To fix this issue, I ensure that both num1 and num2 are treated as integers before they are added. So I use the parseInt() function to convert each string to an integer. 