## Part 1 Answers
1. On line 11 the final value of i is printed, because using var to declare i keeps it in scope after the loop.
2. On line 12 the last discounted price of the list prices is printed.
3. On line 13 the last discounted price of the list prices is printed.
4. The function returns [50, 100, 150], because the 50% discount is applied to all three values, stored in a list, and then returned.
5. On line 11 we get an "i is not defined" error, because let does not keep i in scope after the loop
6. On line 12 we get an "discountedPrice is not defined" error, because let does not keep discountedPrice in scope after the loop
7. On line 13, the last discounted price calculated in the given list of prices is printed, because it was declared at the same level as the console statement in terms of scope.
8. Ignoring the lines that raise errors in order to run the function completely, the function returns [50, 100, 150], because the 50% discount is applied to all three values, stored in a list, and then returned.
9. Ignoring the attempt to reassign a const in the for loop that raises an error, on line 11 we get an "i is not defined" error, because let does not keep i in scope after the loop.
10. Ignoring the attempt to reassign a const in the for loop that raises an error, on line 12 the first discounted price we calculated in the for loop will be printed because once you assign a vlue to a const it can't be changed.
11. Ignoring the attempt to reassign a const in the for loop that raises an error, on line 3 the first value we assigned to finalPrice, which is 0, will be printed because once you assign a vlue to a const it can't be changed.
12. Running the function would fail because you can't reassign a const value, but assuming the lines that raise error were taken out, an empty list would be returned because the list discounted can't be added to.
13a. student.name
13b. student["Grad Year"]
13c. student.greeting()
13d. student["Favorite Teacher"].name
13e. student.courseLoad[0]