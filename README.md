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
FOR LOOPS:



             
