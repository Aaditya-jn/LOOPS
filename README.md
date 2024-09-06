# LOOPS


1)  PRINT THEMULTIPLICATION NUMBER OF A NUMBER n TILL 10
# USING WHILE LOOP:

n = int(input("Enter number", ))

i = 1
<br>
while i < 10:

print(n * i)
<br>
i += 1

# USING FOR LOOP:
```
n = int(input("Enter number", ))

for i in range(1,11):
    print(n * i)
    i += 1
```
[END OF THE FIRST QUESTION].

#2)  PRINT THE ELEMENTS OF THE LIST
      nums = [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]

# USING WHILE LOOP:

idx = 0
<br>
while idx < len(nums):
<br>
print(idx)
<br>
idx += 1

# USING FOR LOOP:

idx = 0
<br>
for elm in nums:
<br>
print(elm)


#3)  SEARCH FOR A NUMBER x IN THIS TUPLE
      numrs = (1, 4, 9, 16, 25, 36, 49, 64, 81, 100)

# USING WHILE LOOP:

x = 64

i = 0

while i < len(numrs):
<br>
if(numrs[i] == x):
<br>
print("Number found at idx", i)
<br>
i += 1



# USING FOR LOOP:


x = 49

idx = 0

for el in nums:
<br>
if(el == x):
<br>
print("Number found at idx", idx)
<br>
idx += 1

    


    
