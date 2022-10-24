1. 3
2. 150
3. 150
4. [50,100,150], it takes in an array of prices and a discount and it multiples every number in the array by the discount and rounds it to the nearest whole number and returns an array of discounted prices.
5. It causes an error because i is only defined in the scope of the for loop as it is a let and thus isn't defined when it's called in line 12
6. Similar to the last question, discountedPrice is only defined within the scope of the for loop and it is a let, so when it is called on line 13, nothing named discountedPrice is defined
7. 150
8. [50,100,150], once again, it takes in an array of prices and the discount and returns an array with the new prices after the discount
9. Error, i isn't defined as it is defined within the scope of the for loop
10. 3, length is a constant that is set on line 4 to the length of the array prices which is 3.
11. [50,100,150], while in line 7, discountedPrice is set to a constant, since it has the same scope of let so a new discountedPrice is created everytime in each iteration of the for loop. Additionally the array discounted isn't constant but instead the reference discounted points to is constant which allows for discounted to be modified and new elements to be pushed to it
12. 
    1.  student.name
    2.  student["Grad Year"]
    3.  
    4.  student["Favorite Teacher"].name
    5.  student.courseLoad[0]
13. 
    1.  32, since 2 maps to '2' so '3' + '2' = '32'
    2.  1, since 3 is converted to a number as - is a mathematical function and 3-2 = 1
    3.  3, since null maps to 0 and 3 + 0 = 3
    4.  3null, since 3 maps to '3' and null to 'null'
    5.  4, since true maps to 1, so 3 + 1 = 4
    6.  0, since both false and null map to 0, so 0 + 0 = 0
    7.  3undefined, strings '3' and 'undefined' are combined
    8.  NaN, since undefined cannot be converted to a valid number
14. 
    1.  true, '2' becomes 2 and 2 > 1
    2.  false, since '2' is greater than '1'
    3.  true, since '2' becomes 2 and 2 == 2
    4.  false, since '2' isn't the same type as 2
    5.  false, since true maps to 1, and 1 != 2
    6.  true, since Boolean(2) converts to true which is same type and equal to true
15. == allows for type conversion before checking equaliy while === checks first to see if they are same type before comparing, so it doens't allow for type conversion
16. 
17. [2,4,6], modifyArray iterates through the array that is passed in and calls doSomething which multiples each number in the array by two and the adds it to a new array. That new array which contains all the doubled values of the inputted array is then returned.
18. 
19. 1
    4
    3
    2