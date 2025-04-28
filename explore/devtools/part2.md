# Part 2
1. The bug is that when we were loading the values into num1 and num2, they were being set to strings, so when they would be added it just concatenated them as strings instead of adding them as number values.
2. I would fix it by making sure that the values were numbers with the Number() function that converts the value to a number.