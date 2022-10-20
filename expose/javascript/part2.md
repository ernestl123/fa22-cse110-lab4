1. Output "3", since the variable i is defined with the var keyword, so it can be accessed anywhere inside the function it is defined. Since i iterates over the length of the list prices, it will be 3 after running the for loop.
2. Output "150", since discountedPrice variable is set with the var keyword, the last update will be on the last item of the list prices, which is 300. As such the value of discountedPrice after running the for loop will be 300 * 0.5 = 150.
3. Output "150", since finalPrice variable's value is being set on line 8 for every iteration in the for loop. Since the value is overridden, it means the final value of finalPrice will be the last iteration, which has discountedPrice = 150. As such, when console outputs the variable it will be the value of Math.round(150 * 100) / 100, which would still be 150.
4. It will return [50, 100, 150], the list of discounted prices respective to the original prices inputted. Line 9 is essentially pushing the updated price for each price in the prices list into the discounted list for each iteration.
5. Causes an error, since the variable i is declared with let keyword, so it cannot be accessed outside the for block.
6. Causes an error, since the variable discountedPrice is declared with the let keyword inside the for loop, so it cannot be accessed outside the block.
7. output 150, since finalPrice is declared inside the function outside the for loop, so it can stil be accessed when the for loop finishes.
8. Return [50, 100, 150], since discounted is declared as a let keyword outside the for loop inside the function, so it can still be accessed inside the for loop and outisde the for loop. It is updated with the new prices and returned.
9. Causes an error because i is defined using let keyword inside the for loop, so it cannot be accessed outside the for block.
10. Output "3", since length is declared outside the for loop inside the function and it is set to be the length of the prices list.
11. Return [50, 100, 150], since discountedPrice is constantly being declared for every iteration in the for loop so it being const does not throw an error, and since discounted variable is not being assigned any new values it will not cause an error either (calling push is not an assignment)
12. 
    1.  student.name
    2.  student["Grad Year"]
    3.  student.greeting()
    4.  student["Favorite Teacher"].name
    5.  student.courseLoad[0]
13. 
    1. '32', since 2 maps to '2'
    2. 1, since '3' maps to 3
    3. 3, since null maps to 0
    4. '3null', since null maps to "null"
    5. 4, true maps to 1 so 3+1=4
    6. 0, since false and null both map to 0
    7. '3undefined', since undefined maps to 'undefined'
    8. NaN, since '3' maps to 3, but undefined maps to NaN in numeric form
14. 
    1.  True, '2' maps to 2
    2.  False, compares first letter of each string first. '2' is greater than '1' so '2' should be greater than '12'
    3.  True, '2' maps to 2
    4.  False, since types are different
    5.  false, since true maps to 1
    6.  true, since 2 is not 0, so Boolean(2) returns true
15. == compares equality with type conversion, but === does not check with type conversion
16. ___
17. The function call modifyArray will iterate through each item in array, and call the callback function, which will take each item and double it. After each callback the new value will be pushed into newArr, which will be returned. This will return an array of the original arr but each element is doubled, so [2, 4, 6]
18. ___
19. 1 4 3 2 