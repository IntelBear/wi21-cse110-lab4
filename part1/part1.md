## Part 1 Answers
Question 1. On line 11 the final value of i is printed, because using var to declare i keeps it in scope after the loop.

Question 2. On line 12 the last discounted price of the list prices is printed.

Question 3. On line 13 the last discounted price of the list prices is printed.

Question 4. The function returns [50, 100, 150], because the 50% discount is applied to all three values, stored in a list, and then returned.

Question 5. On line 11 we get an "i is not defined" error, because let does not keep i in scope after the loop

Question 6. On line 12 we get an "discountedPrice is not defined" error, because let does not keep discountedPrice in scope after the loop

Question 7. On line 13, the last discounted price calculated in the given list of prices is printed, because it was declared at the same level as the console statement in terms of scope.

Question 8. Ignoring the lines that raise errors in order to run the function completely, the function returns [50, 100, 150], because the 50% discount is applied to all three values, stored in a list, and then returned.

Question 9. Ignoring the attempt to reassign a const in the for loop that raises an error, on line 11 we get an "i is not defined" error, because let does not keep i in scope after the loop.

Question 10. Ignoring the attempt to reassign a const in the for loop that raises an error, on line 12 the first discounted price we calculated in the for loop will be printed because once you assign a vlue to a const it can't be changed.

Question 11. Ignoring the attempt to reassign a const in the for loop that raises an error, on line 3 the first value we assigned to finalPrice, which is 0, will be printed because once you assign a vlue to a const it can't be changed.
    
Question 12. Running the function would fail because you can't reassign a const value, but assuming the lines that raise error were taken out, [0, 0, 0] would be returned because finalPrices constant value would be pushed 3 times.

Question 13a. student.name
Question 13b. student["Grad Year"]
Question 13c. student.greeting()
Question 13d. student["Favorite Teacher"].name
Question 13e. student.courseLoad[0]

Question 14a. 32, adding an integer to a string concatenates the integer to the string.
Question 14b. 1, subtracting an integer from an integer-like string performs numerical subtraction.
Question 14c. 3, when adding null to an integer, null is treated as 0.
Question 14d. 3null, when adding null to a string, null is treated as a string.
Question 14e. 4, true is treated as 1 when added to an integer.
Question 14f. 0, false and null are both treated as 0 when adding
Question 14g. 3undefined, undefined is treated as a string when adding
Question 14h. NaN, subtracting undefined from a string is undefined behavior.

Question 15a. true, string is treated as an integer
Question 15b. false, comparison goes from left to right because they are both strings, first bigger character wins
Question 15c. true, string is treated as an integer
Question 15d. false, === checks for matching type and value, '2' and 2 are not the same type 
Question 15e. false, true is treated as 1
Question 15f. true, Boolean(2) converts into true, and true and true both have same type and value.

Question 16. == does not check for matching type, while === does.

Question 17. "How are you?" is printed because true is treated as 1, thus making true == 2 false. however in the second statement, 2 by itself is evaluated to be true, as in shorthand all positive numbers resolve to true.

Question 18. 21, 45, 5, and 2 were printed.

Question 19. [6, 8, 10] is the result. For each number in array, we call doSomething, passing in the number and a function that doubles a number given to it. In do something, it increments the given number by 2 and then calls the doubling function before returning the final result for that number.

Question 20. See part1-question20.js

Question 21. The output is 1, 4, 3, 2 in that order. This is because 1 is printed immediately, 2 has a 1 second delay which makes it print after everything else, 3 has a 0 second delay but still needs time to be set up so it is printed after 4, which is printed immediately upon reaching its line.