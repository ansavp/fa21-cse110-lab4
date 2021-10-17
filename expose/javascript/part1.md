## Part 1A

1. 20
2. 20
3. 20
4. the code gives a reference error because the variable result is of type let and declared within the if. Thus, it is out of scope in line 13.
5. the code gives an error because result is a const and Thus its value cannot be changed but line 7 tries to change the const value, Therefore, we get the error.
6. the code gives an error because the variable result is of type let and declared within the if. Thus, it is out of scope in line 13.

## Part 2

1. Line 12 logs the value of 3 to the console because the loop runs twice and terminates when i becomes 3 which is the length of the prices array. Thus, the final value of i is 3 because that is when the loop terminates.

2. Line 13 logs tha value of 150 to the console. We get 150 because this is the final value of dicountedprice variable after the end of the for loop. At the end of the for loop, discountedprice stores half of the last value (this is calculated as discount is 0.5) in the prices array (half of 300 is 150). Thus, we get 150.

3. Line 14 also logs the value of 150 to the console. As mentioned above the final value of discountedprice at the end of the for loop execution is 150. Line 8 calculates the corresponding finalprice as 150 and stores it. Thus, we get 150.

4. This function would return the follwing array-
[50, 100, 150]
This is because the function runs the for loop and stores the discounted values for each of the unput price at the rate of 0.5 (as given as the parameter) and then stores each of them in an array which it later returns. Thus, we get 50% of the prices passed which is 50, 100 and 150.

5. line 12 will give an error. This is because the variable i has been defined as a let and its scope is within the for loop. As line 12 is outside the for block, it cannot access the variable i and Thus the error.

6. line 13 will give an error. This is because the variable discountedPrice has been defined as a let and Thus its scope is within the for loop. As line 12 is outside the for block, it cannot access the variable discountedPrice and Thus the error.

7. Line 14 also logs the value of 150 to the console. As mentioned above the final value of discountedprice at the end of the for loop execution is 150. Line 8 calculates the corresponding finalprice as 150 and stores it. Thus, we get 150. We are able to access this variable as it is declared as let within the function and Thus its available throughout the function.

8. This function would return the follwing array-
[50, 100, 150]
This is because the function runs the for loop and stores the discounted values for each of the unput price at the rate of 0.5 (as given as the parameter) and then stores each of them in an array which it later returns. Thus, we get 50% of the prices passed which is 50, 100 and 150. Even though the variables are declared as let, we never use any variable outside of its scope and Thus we do not run into any problems.

9. line 11 will give an error. This is because the variable i has been defined as a let and its scope is within the for loop. As line 11 is outside the for block, it cannot access the variable i and Thus the error.

10. line 12 will log the value of 3 to the console. This is because variable length is const and stores the value of the length of prices array which is 3. This value never changes.

11. This function would return the follwing array-
[50, 100, 150]
The explanation of how we get these values is given above. The main part is that we added values to a const array without throwing an error. This is because in const arrays, we can push in new values and change individual values within the array but we cannot reassign the array. Thus, our code does the desired job efficiently.
 
12. A. student.name
B. student['Grad Year']
C. student.greeting.call()
D. student['Favorite Teacher'].name
E. student.courseLoad[1]


13. A. '32'
We get the above output because the number 2 maps to string and then concatenates with the string 3 which is on the left. Thus we get the string '32' as output.
B. 1
We get the above output because the - operator just has one function which is subtraction. Thus, an arithmatic operation happens and therefore the string '3' is casted to the number 3 and then the subtraction takes places yielding the value of 1.
C. 3
We get the above value because addition takes place and in that null maps to 0 on numeric coversion. Thus, 3+0 is 3.
D. 3null
A simple string concatenation takes place and null gets converted to the string 'null' before the concatenation.
E. 4
A numeric addition takes place and true maps to 1. Thus, 3+1 = 4.
F. 0
A numeric addition takes place and both null and false map to 0. Thus we get 0.
G. 3undefined
A simple concatenation takes place and undefined is casted to the string 'undefined' before the concatenation.
H. NaN
We get this because - only does numeric subtraction and subtracting undefined from a string ('3') is impossible.

14. A. true
This because a numeric conversion takes place and '2' becomes the number 2 and as 2>1, therefore we get a true.
B. false
This is because both of them are compared alphabetically and the first character of '12' is smaller than the first character of '2', we get a false.
C. true
A numeric conversion takes place and '2' coverts to the number 2 and as this is not a strict equality, it would return true as data types do not matter.
D. false
This returns false as this is a strict equality and as the data types do not match, one is string ('2') and one is a number (2), we get a false.
E. false
This is because true maps to 1 and as 1 != 2, we get a false.
F. true We get true because Boolean(2) maps to true and now the data types match too, Thus we get true.

15. == only checks equality for the value of the variables and do not care about the data types. It returns true if after casting both of them have the same value.
=== checks for equality of value as well as equality of data types. For this to return true, only if both the value of the variables as well as the data types are the same.

16. done in seperate js file

17. We will get the following array as result-
[2, 4, 6]
We get the above result because within the for loop we call the function doSomething which returns the double for all values in the passed array. Thus 1 becomes 2, 2 becomes 4 and 3 becomes 6 which is the final result we get.

18. done in seperate js file

19. The output of the above code is-
1
4
3
2








