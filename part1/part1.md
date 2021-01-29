1) It will print 3, which is the number of iterations the for loop will make (a final increment occurs at the end)
2) It will print 150 since 300 is the last element to be assigned to "discountedPrice" and it is multiplied with 1/2
3) It will print 150 since we use 300 for the same reason as (2) since 150*100 is a whole number round doesnt change anything and 150*100/100 = 150
4) the function will return [50, 100, 150] since discount = 0.5 the function will in a sense just divide the prices by 2 and for the same reason as (3) finalPrice will be the same as discountedPrice.

5) an error will be thrown since "i" is out of scope
6) an error will be thrown since "discountedPrice" is out of scope
7) it will print 150 since the scope of finalPrice covers the for loop
8) it will return [50, 100, 150] since the scope's dont effect the actual program

9) It will throw an error since i is out of scope
10) It will throw an error since discountedPrice is out of scope
11) It will throw an error since we are trying to re-assign a const
12) since we are returning discounted which relies heavilly on finalPrice, calling this function will return an error

13.A) student.name
13.B) student['Grad Year']
13.C) student.greeting()
13.D) student['Favorite Teacher'].name
13.E) student.courseLoad[0]

14.A) 32, 2 becomes string because string 3 came first
14.B) 1, 3 becomes an int
14.C) 3, null as an int takes the value 0
14.D) 3null, since 3 is a string null becomes the string 'null'
14.E) 4, since true becomes 1 as an int
14.F) 0, since false has value 0 and null as an int has a value 0
14.G) 3undefined, since 3 is a string and "undefined" becomes a string
14.H) NaN, since minus makes the two values "int" type, undefined has the value "NaN" as an int

15.A) true, 2 becomes an int
15.B) false, both are strings so comparison is done alphanumerical.
15.C) true, they become the same type and have the same value.
15.D) false, they have different types.
15.E) false, since false has an int value 0
15.F) True, since boolean(2) has value of true which is of boolean type

16) == does type cast, while === does not

17) How are you?, since 2 =! true but 2 is a valid replacement of true

19) It returns: [ 6, 8, 10 ], It takes each element of an array xi and makes a new array with values 2xi + 2

21)
1
4
3
2