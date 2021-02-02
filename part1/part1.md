<pre>
1. The length of prices array will be printed to console since var has function level scope

2. The last assignment of discountedPrice value will be printed to console since var has function level scope

3. The final updated value of finalPrice will be printed to console since the value of finalPrice is assigned and updated before printing within the function discountPrices(). var has function level scope so finalPrice will be updated and printed correctly

4. It will return [50, 100, 150] since the for loop of the function will do a 50% discount on every element of the input array prices

5. It will be an error since let i only has block level scope and the definition of i is inside of the block (for loop)

6. It will be an error since let discountedPrice only has block level scope and the definition of discountedPrice is inside of the block (for loop)

7. The final updated value of finalPrice will be printed to console correctly since the finalPrice is defined out of the block (for loop). Value assignments inside the block (for loop) will be recorded in finalPrice correctly

8. It will return [50, 100, 150] since the for loop of the function will do a 50% discount on every element of the input array prices

9. It will notice you the error "TypeError: invalid assignment to const 'finalPrice'" since we are reassigning a value to const variable finalPrice at line 7.

10. It will notice you the error "TypeError: invalid assignment to const 'finalPrice'" since we are reassigning a value to const variable finalPrice at line 7.

11. It will notice you the error "TypeError: invalid assignment to const 'finalPrice'" since we are reassigning a value to const variable finalPrice at line 7.

12. It will notice you the error "TypeError: invalid assignment to const 'finalPrice'" since we are reassigning a value to const variable finalPrice at line 7.

13. A: student.name
    B: student['Grad Year']
    C: student.greeting()
    D: student['Favorite Teacher'].name
    E: student.courseLoad[0]

14. A: '32'. Bacause the '3' in the front is a string and + works as a concatenation operator, 2 is treated as a string too (converted into '2') and concatenated behind '3'
    B: 1. Because the '3' is converted into integer 3 and thus this equation becomes a integer subtraction problem 3 - 2
    C: 3. Because the null is converted into integer 0 and thus this equation becomes 3 + 0
    D: '3null'. Because the null is converted into string 'null' and concatenated behind '3' by the + operator
    E: 4. Because the boolean true is converted into integer 1 and thus this equation becomes 1 + 3
    F: 0. Because boolean false and null are both converted into integer 0. This equation becomes 0 + 0
    G: "3undefined". Because undefined is converted into string "undefined" and concatenated behind "3" by the + operator
    H: NaN. Because undefined is converted into integer NaN and "3" is converted into integer 3. 3 - NaN = NaN

15. A: true. Because '2' is converted into integer 2 and integer 2 > integer 1
    B: false. Because string '2' is alphabetically greater than string '12'
    C: true. Because '2' is converted into integer 2 and integer 2 == integer 2
    D: false. Because the types of integer 2 and string '2' are different, they cannot be strictly equal
    E: false. Because the boolean true is converted into integer 1 and integer 1 < integer 2 instead of equals to integer 2
    F: true. Because the result of Boolean(2) is also true. Since the value and type of the left-hand true is the same as the right-hand true, the strict equality holds.

16. ==: Only compares the values of variables on 2 sides. If the types of variables on 2 sides are different, convert the variables into numerical values and compare. Return true if values are the same; return false otherwise
    ===: Also called strict equality. Compares the types and values of variables on 2 sides. Return true if both the types and values of variables on 2 sides are the same; return false otherwise

17. It should print 'How are you?' Because the integer value of true is 1, so (2==true) is false, we won't print 'Hello!'. Then, anything that's not a 0 is true, so our 2 is also true, 'How are you?' is printed.

19. The returned array is [6, 8, 10]
    
    In the 1st iteration of modifyArray():
    newArr.push(doSomething(num[0], function(x){return x * 2}));
    newArr.push(doSomething(1, function(x){return x * 2}));
    newArr.push(function(1 + 2){return x * 2});
    newArr.push(3 * 2);
    newArr.push(6);

    In the 2nd iteration of modifyArray():
    newArr.push(doSomething(num[1], function(x){return x * 2}));
    newArr.push(doSomething(2, function(x){return x * 2}));
    newArr.push(function(2 + 2){return x * 2});
    newArr.push(4 * 2);
    newArr.push(8);

    In the 3rd iteration of modifyArray():
    newArr.push(doSomething(num[2], function(x){return x * 2}));
    newArr.push(doSomething(3, function(x){return x * 2}));
    newArr.push(function(3 + 2){return x * 2});
    newArr.push(5 * 2);
    newArr.push(10);

    So the result is [6, 8, 10]

21. The output is:
    1
    4
    3
    2
</pre>
