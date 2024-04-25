1. It will print '3' as i is incremented until i breaks the rule of being less than the length of the prices array which is 3.
2. It will print '150' as discountedPrice will be updated 3 times, and on the last iteration it will be 300 * (1 - 0.5)
3. It will prine '150' because the final price will be the last updated iteration which is rounding the outcome of question 2.
4. It will return the array, discounted, with the values [ 50, 100, 150 ] as it is a result of applying the discount to all elements in prices.
5. It would cause an error because i is assigned by let which means that it cannot be accessed outside the for loop block.
6. It would cause an error because discountedPrices is assigned by let which means that it cannot be accessed outside the for loop block.
7. It will print '150' even though it is assigned let, it is this within the same code block of the discountedPrices function.
8. It will return finalPrice which is [ 50, 100, 150 ] as all the all the processes are within the function block.
9. We will see an error since i is declared with let which makes it not accessible outside of the for loop.
10. It will print '3' since length is declared a constant an equivalent to the length of prices which is 3 and is not changed throughout the code.
11. It will return the final discounted Array, [ 50, 100, 150 ], as although discounted must point to the created array, it can hold values that are updated by the rest of the function.
12. 
    A. student.name;

    B. student['Grad Year'];

    C. student.greeting();

    D. student['Favorite Teacher'].name;

    E. student.courseLoad[0];
13. 
    A. '32'. This is because the + operator conjoins the two but in the format of a string.

    B. 1 because the - operand is for number types and therefore converts the string to an int.

    C. 3 since null is treated as 0.

    D. '3null' since 3 is a string it would conjoin the null to be a string

    E. 4 as the + operand would treat true as 

    F. 0 since they would both default to 0 when there is a + operand

    G. '3undefined' since we are adding with the existence of a string so the other type would be converted to a string

    H. NaN since neighter are numbers we cannot preform any form of subtraction with the existence of undefined as it is not a number.

14. 
    A. True since the string is converted to a number in comparison operations

    B. True as the same logic applies here with the string converting to an int

    C. False as both would be converted to numbers and be compared similarly to a 2 < 12

    D. True as the string would be converted to a nubmer and be compared similar to a 2 == 2

    E. This would output false since the === operator would compare value and type in which the string and int are not the same

    F. False since true is converted to 1 and 1 != 2

    G. True since the boolean(2) holds the value of true

15. The main difference between == and === is that === checks the type as well, meaning that if the compared types are not the same it would return false.

17. It first initializes the array newArr as empty and then proceeds through the for loop to push need elements into newArray depending on the input array length (in this case 3). In each iteration, the callbackfunction is called during each push which multiplies each existing element in array by 2 which results in the final array of [2, 4, 6].

19. the output would be 1 4 3 2 since the 1 and 4 are printed immediately when the line runs and 3 when the queue ends and 2 last (after 1 second).

