# Part 2
1. The value 3 will be printed
2. The value 150 will be printed
3. The value 150 will be printed
4. It returns an array with values [50, 100, 150] because it goes through the array and applies the discount to all the prices, in this case halving them
5. This line returns an error because we used the _let_ keyword for i, so we cannot access it when we are outside of its scope, the for loop block
6. This line returns an error because we used the _let_ keyword for discountedPrice, and since we are in a different block than where it was initalized (the variable was initalized within the for loop), it is not within our scope to call it at line 13 so we get an error
7. The value 150 will be printed
8. It returns an array with values [50, 100, 150] because it goes through the array and applies the discount to all the prices, in this case halving them. In this case, using _let_ does not change the output because we get the value we need into finalPrice, which is then pushed into the array
9. This line returns an error because we used the _let_ keyword for i, so we cannot access it when we are outside of its scope, the for loop block
10. The value 3 will be printed
11. It return an array with values [50, 100, 150]. Although it looks the same as the other return values, it is only because the discount price we are working with is 0.5 so the discount and the value after discount is the same. In this function it returns how much the discounted amount is.
12. 
    1.  student.name
    2.  student['Grad Year"]
    3.  student.greeting()
    4.  student['Favorite Teacher'].name
    5.  student.courseLoad[0]
13. 
    1.  '32'; if there is a + with a string and a number the number will get converted to a string and be concatenated
    2.  1; - is a numeric operator so it will convert the 3 to a number value and subtract 2 from it
    3.  3; null is converted to 0 in numerical operation
    4.  '3null'; since 3 is a string it is taken as a concatenation and adds 'null' to the 3
    5.  4; the boolean value of true is 1 in numerical operations
    6.  0; false and null are both converted to 0 in numerical operations
    7.  '3undefined'; since 3 is a string it is taken as a concatenation and adds 'undefined' to the 3
    8.  NaN; undefined is NaN in numerical operation so the result has to be NaN
14. 
    1.  true; '2' is converted to a number and is greater than 1, so true
    2.  false; when comparing strings, it does it lexicographically, and since 2 comes after 1 when comparing the first characters of the string, it should be greater not less, so false
    3.  true; it converts '2' to the number 2 first, then compares 2 to 2, which is equal so true
    4.  false; === is strictly equal to, and since the types dont match, returns false
    5.  false; true is converted to 1, and 1 != 2 so false
    6.  true; Boolean(2) is true so true === true which returns true
15. == checks to see if the values are the same after it tries to convert them to the same type, which is why something like 2 == '2' returns true. === is strictly equal to, making sure that it has the same value and type, so that same example would return false.
16. 
17. The result is an array with values [2, 4, 6] will be returned. This is because when we call modifyArray, it goes through the array and calls the callback on each value. For our case, the callback is a value that doubles the number that is passed, so it goes through and doubles the values in the array.
18. 
19. 1 4 3 2