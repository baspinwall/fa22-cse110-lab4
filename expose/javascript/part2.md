1. 3, as we increment i until it is prices.length, 3 here, is a var and in scope
2. 150, as discountedPrice will be the last calculated value in all the loops, so 300 * (1 - 0.5)
3. 150, as finalPrice will be the last calculated value from all loops, here it is 150 * 100 rounded, then divided by 100, so 150
4.  [50, 100, 150], as it will calculate all the values correctly, halving them
5.  This will error since i is a let and is not in scope
6.  This will error since discountedPrice is a let and not in scope
7.  This will print 150, since finalPrice is defined in the same scope.
8.  This will return [50, 100, 150], as it will calculate all the values correctly, halving them, and the variable is in scope
9.  There will be an error, as i is a let and not in scope
10. It prints 3, as length is a const defined in scope
11. It returns [50, 100, 150], as the code correctly calculates the values, multiplying all prices[i] by 1-.5 and adding them to the list (const list can be changed)
12. 
    A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. 
    A. '32', 2 converts to '2'
    B. '1', '3' converts to 3
    C. 3, null converts to 0
    D. '3null', null converts to 'null'
    E. 4, true converts to 1
    F. 0, false and null convert to 0
    G. '3undefined', undefined converts to 'undefine'
    H. undefined, '3' converts to 3 and 3-undefined is undefined
14. 
    A. true, '2' converts to 2
    B. false, no conversion so '2' > '12'
    C. true, '2' converts to 2
    D. false, no type conversion
    E. false, true converts to 1
    F. true, Boolean(2) evaluates to true
15. == performs type conversion before checking equality if necessary, === does not, so it returns false if different types
16. part2-question16.js
17. [2,4,6] is returned since the modifyArray function creates a new list which it populates by calling the passed in function on each element of the passed in list, in this case doubling all elements
18. part2-question18.js
19. 1
    4
    3
    2
    1 is printed, then 3 is delayed by a small amount, 2 is delayed, so 4 then 3 then 2
20.