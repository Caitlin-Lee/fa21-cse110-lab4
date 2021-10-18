1. At line 12, it will print 3. This is due to i being declared as a var. This allows it to be called outside the for loop because it's in function scope. The loop continues iterating up to prices.length and breaks out the loop at i = 3.
2. It will print 150 at line 13. At the very last iteration of the for loop, discountedPrice is set to 300 * (1-0.5) = 150. 
3. At line 14, it will print 150. In the last iteration of the for loop, discountedPrice is 150. finalPrice = 150 * 100 / 100 = 150.
4. This function will return [50, 100, 150]. discountPrices takes in a list of prices and the discount. It loops through the prices and calculates the discountedPrice. It calculates the finalPrice after all the discounts and pushes it to discounted. The function then returns discounted. In this case it goes through 100, 200, and 300. It calulates 50, 100, and 150 and pushes it into the final result.
5. This code causes an error (reference error: i is not defined). This occurs because i was declared using let. i is only in scope in that for loop. Line 12 attempts to call it outisde the for loop.
6. This code causes an error (reference error: discountedPrice is not defined). This occurs because discountedPrice was declared using let. discountedPrice is only in scope in that for loop. Line 12 attempts to call it outisde the for loop.
7. At line 14, 150 is printed. This is because the variable finalPrice is in scope with where the console.log is called. Therefore, it is able to be printed.
8. This function returns [50, 100, 150]. The function declares discounted and finalPrice. The for loop would go through 0 to the length of prices, calculate the discounted price, and push that discounted price to finalPrice. Once the for loop terminates, it will return the full finalPrice list. There are no out of scope errors and all the let variables are defined correctly.
9. This would cause an error (reference error: i is not defined). This is because i is delcared with let. This would only allow i to be in the scope of the for loop. Line 11 attempts to call it outside of its scope (outside of the for loop).
10. Line 12 would print 3. This is because length is declared earlier under const. It is not being reassigned and it is in scope with line 12. Therefore it prints the length of price without any errors.
11. This function returns [50, 100, 150]. The function declares discounted and length. The for loop would go through 0 to the length, calculate the discounted price, and push that discounted price to discounted. Once the for loop terminates, it will return the full discounted list. There are no out of scope errors and all the let and const variables are defined correctly.
12. notation:
    * student["name"]
    * student["Grad Year"]
    * student.greeting()
    * student["Favorite Teacher"].name
    * student["courseLoad"][0]
13. Arithmetic:
    * Output: '32' - 2 gets converted into a string and gets appended to the end of '3', resulting in '32'
    * Output: 1 - '3' gets converted numerically and calculates 3 - 2, result in in 1
    * Output: 3 - null gets converted to 0 and calculates 3 - 0. resulting in 3
    * Output: '3null' - null gets converted into a string and gets appended to the end of '3', resulting in '3null'
    * Output: 4 - true gets converted to 1 and calculates 1 + 3, resulting in 4
    * Output: 0 - false and null both get converted to 0 and calculates 0 + 0, resulting in 0
    * Output: '3undefined' - undefined gets converted to a string 
    * Output: NaN - undefined gets converted to NaN and since we cannot change any of the types here to output something, it will result in NaN

14. Comparison:
    * Output: true - 2 gets converted numerically and calculates whether 2 > 1 resulting in true
    * Output: false - it checks the first character of the 2 strings, since '2' is greater than '1' it returns false
    * Output: true - The double equal sign is an equality test, therefore it checks if they are the same regardless of type. Therefore this will return true.
    * Output: false - The triple equal sign checks whether they are the same type, since they aren't this returns false
    * Output: false - this returns false because true converts to 1 and 1 is not equal to 2
    * Output: true - this is true because both types are boolean true
15. The == is an equality test while === checks the equality without the type conversion. 
16. See part2-question16.js
17. This should return [ 2, 4, 6]. modifyArray is called using [ 1, 2, 3] and doSomething as parameters. It creates a new array first. Then it goes into a for loop that iterates through the entire array [1, 2, 3]. For each item in the array it pushes the result of callback (in this case the function doSomething) on the item in the array. doSomething multiplies numbers by 2, so newArr gets populated with [1, 2, 3] multiplied by 2. Then it returns newArr which is now [2, 4, 6].
18. See part2-question18.js
19. Output will be: 1  
4  
3  
2  
