1. At line 12, the code will print '3' because i is accessible in the function scope, and this is the value i holds when the loop exits.

2. At line 13, the code will print '150' because discountedPrice is var variable and it will leave the loop as the last element in prices / (1 - discount).

3. At line 14, the code will output '150', which is the last computed finalPrice in the loop for the price of 300 discounted by 50%.

4. This function is called with the parameters ([100, 200, 300], 0.5), it will return [50, 100, 150]. It loop for each element in the price and add discounted values to the list. Then return the list.  

5. At line 12, the code will cause a ReferenceError due to the scope of the i variable. It cannot be access by line 12 because it use let and defined in the for loop.

6. At line 13, the code will cause a ReferenceError due to the scope of the discountedPrice variable. It cannot be access by line 13 because it use let and defined in the for loop.

7. At line 14, the code will print the value '150' of finalPrice to the console because the finalPrice, the for loop and line 14 was defined in the same scope so finalPrice are reassigned by the for loop and the final result is 150.

8. This function is called with the input [100, 200, 300] and a discount of 0.5, it successfully returns [50, 100, 150]. It loop for each element in the price and add discounted values to the list. Then return the list.

9. At line 11, the code will cause a ReferenceError because the variable i is declared with let inside the for loop and hence is only accessible within the scope of that loop.

10. At line 12, the code will output '3' to the console, reflecting the number of items in the prices array provided to the function. It was declared in the same scope as line 12 and it is a constant. So line 12 will print its initial value 3.

11. This function is called with the input [100, 200, 300] and a discount of 0.5, it successfully returns [50, 100, 150]. It loop for each element in the price and add discounted values to the list. Then return the list. The discounted list is const but the code only pushes element to it rather than reassingn it. So it still successfully return the expected value.

12. A: student.name
    B: student['Grad Year']
    C: student.greeting()
    D: student['Favorite Teacher'].name
    E: student.courseLoad[0]

13. A: '32' 
        In javascript, 2 is converted to '2', and the result is the concatenation of '3' and '2', which is '32'.
    B: 1 
        JavaScript converts the string '3' to the number 3, and performs the subtraction 3 - 2, resulting in 1.
    C: 3
        JavaScript treats null as 0. Therefore, the operation becomes 3 + 0, which equals 3.
    D: '3null'
        null is converted to the string 'null'. Thus, '3' + 'null' results in '3null'
    E: 4
        JavaScript converts true to 1 in numerical contexts. Therefore, the operation becomes 1 + 3, which equals 4.
    F: 0
        In JavaScript, false is converted to 0 and null is also treated as 0 in numerical operations. So, 0 + 0 equals 0
    G: '3undefined'
        undefined is converted to the string 'undefined', resulting in '3undefined'.
    H: NaN
        While '3' can be successfully converted to 3, undefined converts to NaN (Not-a-Number). Any arithmetic operation involving NaN results in NaN.

14. A: true
        When comparing a string with a number, JavaScript converts the string to a number. Here, '2' becomes 2, and 2 is indeed greater than 1.
    B: false
        When comparing strings, JavaScript uses lexicographical order. The character '2' is lexicographically greater than '1', so '2' is considered greater than '12'.
    C: true
        The string '2' is converted to the number 2, and since 2 equals 2, the result is true.
    D: false
        The === operator checks for equality without type conversion. Since the types differ, the result is false.
    E: false
        When using the == operator, true is converted to 1, not 2. Therefore, 1 does not equal 2, resulting in false.
    F: true
        The === operator checks both value and type. Boolean(2) evaluates to true because any non-zero number in JavaScript is truthy. Since both operands are true and both are Boolean types, the result is true.

15. '==' and '===' both are used for comparison. '==' includes type convertion but '===' does not. '===' compares both value and type.

16. see part2-question16.js

17. The output of modifyArray([1,2,3], doSomething) will be [2, 4, 6].
    Function Initialization:
     modifyArray initializes an empty array newArr.
    Looping Through Elements:
        A for loop iterates over each element in the input array [1, 2, 3].
    Callback Execution:
        During each iteration, the current element of the array (array[i]) is passed to the callback function doSomething.
        Inside doSomething, the passed number is multiplied by 2.
    Storing the Result:
        The result of the callback function is then pushed into newArr.
        For each element:
            When i = 0: doSomething(1) returns 2
            When i = 1: doSomething(2) returns 4
            When i = 2: doSomething(3) returns 6
    Return the Modified Array:
        After the loop completes, modifyArray returns the newArr, which now contains [2, 4, 6].

18. see part2-question18.js

19. 1
    4
    3
    2
