# Loops

```
DEFINITION:
A LOOP IS A BLOCK OF CODE WHICH GETS REPEATED OVER AND OVER AGAIN UNTIL SOME CONDITION STOPS IT.
THERE ARE TWO TYPES OF LOOPS; WHILE LOOP ND FOR LOOP.

```

```
WHILE LOOP: WHILE LOOPS RUN UNTIL SOME CONDITION IS TRUE.
It starts with while keyword followed by a testcondition and a semicolon.
Loop body evaluates repeatedly. Each line has a indentation of 4 spaces.

WHEN A WHILE LOOP IN PYTHON IS EXECUTED, FIRST PYTHON CHECKS THAT IF THE
TEST CONDITION IS TRUE OR FALSE, IF IT IS TRUE THEN THE CODE IS EXECUTED
AND WE THE THE DESIRED OUTPUT. IF IT IS FALSE THEN THE CODE IN THE LOOP BODY
IS NOT EXECUTED BUT THE REST OF THE PROGRAM IS EXECUTED.

If we execute a code in IDLE:

n = 1
while n < 6:
    print(n)

THE CODE ABOVE IS AN INFINITE CODE AND IS NEVER GOING TO END BCOZ
WHEN WE SEE THE TESTCONDITION, IT TELLS THAT WHEN VALUE OF n IS LESS THAN
6, PRINT n. THE VALUE OF n IS 1 . SO IT KEEPS PRINTING 1 INFINITE TIMES.

n = 1
while n < 6:
    print(n)
    n += 1

THIS CODE PRINTS THE NO.S FROM 1 TO 5. NOTE HERE THAT NOW 1 DOES NOT KEEP
PRINTING INFINITE TIMES AS WE HAVE PASSED A CONDITION THAT WHEN VALUE OF N IS
LESS THAN 6, PRINT n. AS WELL AS WE ARE GOING TO INCREASE THE VALUE OF N BY 1.
SO THE NEXT VALUE OF n BECOMES 2 THEN 3,4,5. TILL 5 IT STOPS BECOZ THE TESTCONDITION
IS TILL 5 ONLY AND WE GET THE NUMBERS PRINTED FROM 1 TO 5.

```

```
FOR LOOP: A FOR LOOP EXECUTES A SECTION OF CODE ONCE FOR AN ITEM IN A COLLECTION OF ITEMS.
It starts with a for keyword, followed by membership expression and ends with a semicolon(:).
THE LOOP BODY CONTAINS THE CODE AND HAS AN INDENTATION OF 4 SPACES.

>>>name = "Aaditya"
>>>for i in name:
>>>    print(i)
   
A
a
d
i
t
y
a


~FOR LOOPS ARE BETTER THAN WHILE LOOPS BECOZ THEY ARE EASY TO READ AND TYPE. FOR EX:
A code to print all letters of the word python in a while loop:


str = "Python"
idx = 0

while idx < len(str):
    print(str[idx])
    idx += 1

    
P
y
t
h
o
n

WHEREAS TO PRINT ALL LETTERS OF THE WORD python IN A FOR LOOP:

val = "Python"
for i in val:
    print(i)

    
P
y
t
h
o
n

```

```
RANGE FUNCTION: IT GIVES RANGE OF NUMBERS

range(0,3) is 0, 1, 2


range(start, stop, gap). THIS IS THE BASIC CONCEPT
LIKE range(2, 20, 2) PRINTS THE TABLE OF 2 TILL 20 AS THERE IS GAP == 2 SO IT CREATES A MULTIPLICATION TABLE WHICH IS NOT THERE IN WHILE LOOPS.


SUPPOSE THIS BELOW CODE:

for n in range(10, 20):
print(n * n)

WHAT HAPPENS HERE IS WHEN VAL OF N IS 10 THEN 10*10 IS CALCULATED WHICH IS 100
TILL 19 IT HAPPENS BUT NOT FOR 20

range(10,20)
print(n * n)
THIS MEANS THAT WHEN WE START FROM 10 AND FINISH TILL 20
THEN WHAT HAPPENS IS 10*10 = 100 IS PRINTED THEN 11*11 = 121 IS PRINTED TILL 19*19 = 361.

```

```
A PRACTICAL EXAMPLE:

The following program asks the user to input an amount and then displays how to split that amount be-
tween 2, 3, 4, and 5 people and upto 3 decimal places:


amount = float(input("Enter the amount : "))

for people i nrange(2, 6):
    print(f"{people} people : rupee {amount / people:,.3f } each" )


Enter an amount: 10
2 people: rupee 5.000 each
3 people: rupee 3.333 each
4 people: rupee 2.500 each
5 people: rupee 2.000 each

```

```
NESTED LOOPS:
We can put loops in loops too:

TYPE THIS CODE IN IDLE:

for n in range(1, 4):
    for j in range(4, 7):
        print(f"n = {n} and j = {j}")

n = 1 and j = 4
n = 1 and j = 5
n = 1 and j = 6
n = 2 and j = 4
n = 2 and j = 5
n = 2 and j = 6
n = 3 and j = 4
n = 3 and j = 5
n = 3 and j = 6


The explanation of the above code is that when we write the for loop for n starting from
1 till 3 and then we again write a for loop for j starting from 4 till 6 and then we write print
using the f strings then first n is assigned to the value 1 and in next line value of j is assigned as 4
and "n = 1 and j = 4" is printed. Now we expect the loop to be started from outer(n wala for loop) but in reaity
i starts from inner(j wala for loop) and when the inner loop starts, the value of n is assiggned 1 only till j apni max
range tk nhi pahunch jata.



When Python enters the body of the ﬁrst for loop, the variable n is assigned the value 1.
Then the body of the second for loop is executed and j is assigned the value 4.
The ﬁrst thing printed is n = 1 and j = 4.

After executing the print() function, Python returns to the inner for
loop, assigns to j the value of 5, and then prints n = 1 and j = 5. Python
doesn’t return the outer for loop because the inner for loop, which is
inside the body of the outer for loop, isn’t done executing.
Next, j is assigned the value 6 and Python prints n = 1 and j = 6. At
this point, the inner for loop is done executing, so control returns to
the outer for loop.
The variable n gets assigned the value 2, and the inner for loop executes
a second time. That is, j is assigned the value 4 and n = 2 and j = 4 is
printed to the console.

```





             
