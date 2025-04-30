1. Line 12 will print out the value 3 because the vairable i is declared with var so it has function scope. Therefore, after the loop ends, i will still have the value that caused the loop to end.
2. Line 13 will print out the value 150 because the variable discountedPrice is declared with var so it has function scope. Therefore, discountedPrice keeps its value even after the loop ends which is 300 * 0.5 = 150.
3. Line 14 will print out the value 150 because finalPrice is declared with var and has function scope. After the loop ends, the value of finaPrice from the last iteration stays which is Math.round(150 * 100) / 100 = 150.
4. The function returns an array [50, 100, 150] because the function first creates an empty array called discounted, then in the for loop, it takes the discounted price for each price [100, 200, 300] and pushes it in the array.
5. The code returns an error, ReferenceError: i is not defined, because the variable i is declared with let inside the for loop which gives it block scope. So when it is called in line 12 outside the loop, i is not accessible.
6. The code returns an error, ReferenceError: discountedPrice is not defined, because discountedPrice is declared with let inside the for loop which gives it block scope. So when it is called in line 13 outside the loop, discountedPrice is not accessible.
7. Line 13 will print out the value 150, because finalPrice is declared with let at the function level. Therefore, since the variable is being called within the function, finalPrice is able to be accesssed.
8. The function will return an array [50, 100, 150] because the function first creates an empty array called discounted, then in the for loop, it takes the discounted price for each price [100, 200, 300] and pushes it in the array. All variables are accessed correctly within their scope.
9. The code causes an error, ReferenceError: i is not defined, because the variable i is declared with let inside the for loop which gives it block scope. So when it is called in line 11 outside the loop, i is not accessible.
10. Line 12 will print the value 3 because the variable length is declared with const and assigned the value of prices.length, which is 3. The variable length is defined with function scope so it is accessible at line 12.
11. The function will return an array [50, 100, 150] because even though the variable discounted is declared with const, you can still push items to the array because the reference to the array is not being changed. You are allowed to changed changed the object the variable references not the reference itself.
12. A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. A. '32' (number 2 maps to string '2', string concatentation)
    B. 1 ('3' maps to number 3, numeric operation)
    C. 3 (null maps to number 0, numeric operation)
    D. '3null' (null maps to string 'null', string concatenation)
    E. 4 (true maps to number 1, numeric operation)
    F. 0 (false maps to number 0 and null maps to number 0, numeric operation)
    G. '3' + undefined = '3undefined' (undefined maps to string 'undefined', string concatenation)
    H. NaN (undefined maps to NaN, numeric operation)
14. A. true ('2' maps to number for comparison)
    B. false ('2' comes after '1')
    C. true ('2' becomes a number 2)
    D. false (types are different)
    E. false (true maps to 1)
    F. true (both sides are true)
15. == means loose equality and performs type conversion before comparing the values. === means strict equality and does not perform type conversion before comparing and requires both the value and type to match to be true.
17. [2, 4, 6]. modifyArray first creates an empty array newArr. It then iterates through each element of the array input [1, 2, 3]. For each element, it calls the function doSomething with the element from the input array as the parameter and then pushes it into newArr. doSomething multiplies the number by 2 and returns it. newArr is then returned at the end after the for loop with [2, 4, 6]
18. 
    1
    4
    undefined
    3
    2