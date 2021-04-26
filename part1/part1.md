## Part 1a
### var declaration
1. values added: 20
2. values printed: 20
### let declaration
1. values added: 20
2. Error: result is not defined, as let defines result only in the scope of the if statement
### const declaration
1. Error: cannot reassign a constant variable
2. Error: cannot reassign a constant variable

## Part 1b
1. 3 will be printed because i is a var, so its scope is the entire function after it is declared. The array prices had a length of 3, so the loop ran 3 times, i starting at 0 and ending at 3
2. 150 will be printed because discountedPrice is a var, so its scope is the entire function after it is declared. The final discounted price was 50% of 300, which is 150
3. 150 will be printed because finalPrice is a var, so its scope is the entire function after it is declared. The final price was 150
4. This function will return an array the same length as prices, where each entry of the array is the discounted version of the original prices. In this case, the discount was 50%, so the entries would be [50, 100, 150]
5. Error: i is not defined since it is declared using let, its scope is only inside the for loop block. Outside the for loop, i is not defined
6. Error: discountedPrice is not defined since it is declard using let, its scope is only inside the for loop block. Outside the for loop, discountedPrice is not defined
7. 150 will be printed because the scope of finalPrice is the entire function block, so finalPrice is defined at the console.log statement
8. This function will return an array the same length as prices, where each entry of the array is the discounted version of the original prices. In this case, the discount was 50%, so the entries would be [50, 100, 150]
9. Error: i is not defined since it is declard using let, its scope is only inside the for loop block. Outside the for loop, i is not defined
10. 3 will be printed because the scope of length is the entire function block, so length is defined at the console.log statement
11. This function will return an array the same length as prices, where each entry of the array is the discounted version of the original prices. In this case, the discount was 50%, so the entries would be [50, 100, 150]. Even though the array is a const, the object itself is still mutable so elements can be pushed into the array, as long as the array itself is not reassigned
12. Notation for:
    1.  student.name
    2.  student['Grad Year']
    3.  student.greetin()
    4.  student['Favorite Teacher'].name
    5.  student.courseLoad[0]
13. Arithmetic
    1.  "32", since the + operation is used to concatenate strings as well, the 2 is mapped to a string and concatenated with 3 to give 32
    2.  1, since the - operation is only used on numbers, the '3' is mapped to an integer and normal arithmetic occus
    3.  3, since null maps to 0
    4.  "3null", since null becomes a string and the + operation is then used to concatenate strings
    5.  4, since true maps to 1
    6.  0, since both false and null map to 0
    7.  "3undefined", since the + operation acts as string concatenation
    8.  NaN, since the operation - is not defined on strings
14. Comparison
    1.  true, since '2' is converted to the integer 2 and it is larger than 1
    2.  false, since the first character of '2' is larger than the first character of '12', so '2' > '12'
    3.  true, since '2' is converted to the integer 2 and it is equal to 2
    4.  false, since '2' is not the same type as 2
    5.  false, since true is converted to the integer 1 and is not equal to 2
    6.  true, since Boolean(2) is true, and true is equal to true
15. The `==` converts operands of different types to numbers. The `===` is a strict equality operator, and checks the equality without type conversion. In other words, if `a` and `b` are different types, then `a === b` immediately returns false.
16. In part1b-question16.js
17. The result would be the array [2, 4, 6]. For each element of the original array, doSomething multiplies the element by 2 and pushes it to the new array. The first element is 1, so doSomething returns 2. The second element is 2, so doSomething returns 4. The third element is 3, so doSomething returns 6.
18. In part1b-question18.js
19. The function prints 1, then 4, then 3, and finally 2.
