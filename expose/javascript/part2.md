1. Line 12 will output 3. The var i will reach the length of the prices array through the loop, and will continue to exist even after the loop is terminated.
2. Line 13 will output 150. The var i will be 2 during the last iteration of the loop. This will set var discountedPrice to the third array value (300) and multiply it accordingly with the given discount.
3. Line 14 will output 150. It will take the discountedPrice variable and round it back to itself.
4. The function will return the array [50, 100, 150]. It correctly applies the given 50% discount to the given array of [100, 200, 300].
5. Line 12 will throw an error. Let i cannot be accessed outside of the block of the loop.
6. Like line 12, line 13 will also throw an error because the the let discountedPrice cannot be accessed outside of the block of the loop.
7. Line 14 will throw the same error. Let finalPrice cannot be accessed outside of the block of the loop.
8. The function will return the array [50, 100, 150]. It correctly applies the given 50% discount to the given array of [100, 200, 300]. The loop is able to update the discounted array because it is within the same block.
9. Line 11 will throw an error. Let i cannot be accessed outside of the block of the loop.
10. Line 12 will output 3. It will correctly give the length of the prices array. Const length can be accessed through the block of the function and is unable to be changed after its initialization.
11. The function will return the array [50, 100, 150]. Const discountedPrice is able to be used to push to the const discounted array as each iteration of the loop is effectively making a "new" block and thus a "new" const discountedPrice variable.
12. A. student.name
    B. student['Grad Year']
    C. student.greeting
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. A. '32': + operator used with string will perform string concatenation
    B. 1: - operator will convert string '3' to a number and perform the subtraction
    C. 3: Null is equated to 0 with arithmetic
    D. '3null': String concatenation is performed and null is converted to a string
    E. 4: True is converted to 1 with arithmetic
    F. 0 Both false and null are converted to 0 and arithmetic is performed
    G. '3undefined': String concatenation is performed and undefined is converted to a string
    H. NaN: String '3' is converted to a number but undefined is converted to NaN
14. A. True: String '2' is converted to a number and then compared
    B. False: Two strings are compared by comparing first characters based on their dictionary order
    C. True: String '2' is converted to a number and then compared
    D. False: === operator compares value and variable type
    E. False: True is converted to 1 and then compared
    F. True: 2 is converted to true and then compared
15. == operator will convert variable types before comparing values if necessary. === operator compares both variable types and values.
16. See part2-question16.js
17. The result will be [2, 4, 6]. The newArr array is created. The loop goes through each element in the given array, running it through the doSomething function, which multiplies it by 2, and adding it to the newArr array. The newArr array then holds what it is essentially the given array with each element multiplied by 2.
18. See part2-question18.js
19. Output is as below

1
4
3
2
