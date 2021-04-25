## Part 1a

1. prints `values added: 20`
2. prints `final result: 20`
3. prints `values added: 20`
4. returns an error, since the variable `result` cannot be accessed outside of the `if` statement
5. returns an error, since the variable `result` cannot be reassigned after it is assigned its initial value of `0`
6. returns an error, since the variable `result` cannot be reassigned after it is assigned its initial value of `0`

## Part 1b

1. prints `3`
2. prints `150`
3. prints `150`
4. returns `[50, 100, 150]`, since these are the discounted prices that result when applying a `50%` discount to the input prices `[100, 200, 300]`
5. returns an error, since the variable `i` cannot be accessed outside of the `for` loop
6. returns an error, since the variable `discountedPrice` cannot be accessed outside of the `for` loop
7. prints `150`
8. returns `[50, 100, 150]`, since these are the discounted prices that result when applying a `50%` discount to the input prices `[100, 200, 300]`
9. returns an error, since the variable `i` cannot be accessed outside of the for loop
10. prints `3`
11. returns `[50, 100, 150]`, since these are the discounted prices that result when applying a `50%` discount to the input prices `[100, 200, 300]`
12. A. `student.name`  
    B. `student['Grad Year']`  
    C. `student.greeting()`  
    D. `student['Favorite Teacher'].name`  
    E. `student.courseLoad[0]` 
13. A. `'3' + 2 = '32'` since integers map to their string representation  
    B. `'3' - 2 = 1` since strings map to their numeric representation  
    C. `3 + null = 3` since `null` maps to the integer `0`  
    D. `'3' + null = '3null'` since `null` maps to the string `'null'`  
    E. `true + 3 = 4` since `true` maps to the integer `1`  
    F. `false + null = 0` since `false` and `null` both map to the integer `0`  
    G. `'3' + undefined = 3undefined` since `undefined` maps to the string `'undefined'`  
    H. `'3' - undefined = NaN` since `undefined` maps to the integer `NaN`
14. A. `'2' > 1 = true` since `'2'` maps to the integer `2`, which is greater than `1`  
    B. `'2' < '12' = false` since `'2'` comes after `'12'` lexicographically  
    C. `2 == '2' = true` since `'2'` maps to the integer `2`, which is equal to `2`  
    D. `2 === '2' = false` since `2` is an integer and `'2'` is a string, which are not the same type  
    E. `true == 2 = false` since `true` is a boolean and `2` is an integer, which are not the same type  
    F. `true === Boolean(2) = true` since `Boolean(2)` evaluates to the boolean `true`, which is equal to `true`
15. the `==` operator casts its arguments if they are of different types, and then checks for equality. on the other hand, the `===` operator checks for equality of its arguments only if they are of the same type
16. see `part1b-question16.js`
17. returns `[2, 4, 6]`, since at each iteration of the `for` loop, we take a value from `array`, and double it using the function `doSomething`, referenced by `callback`
18. see `part1b-question18.js`
19. prints:  
    `1`  
    `4`  
    `3`  
    `2`