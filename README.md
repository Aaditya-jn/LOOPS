# LOOPS


1)  PRINT THEMULTIPLICATION NUMBER OF A NUMBER n TILL 10
# USING WHILE LOOP:

n = int(input("Enter number", ))

i = 1
while i < 10:

print(n * i)
i += 1

# USING FOR LOOP:

n = int(input("Enter number", ))

for i in range(1,11):
print(n * i)
i += 1



2)  PRINT THE ELEMENTS OF THE LIST
      nums = [1, 4, 9, 16, 25, 36, 49, 64, 81, 100]

# USING WHILE LOOP:

idx = 0
while idx < len(nums):
print(idx)
idx += 1

# USING FOR LOOP:

idx = 0
for elm in nums:
print(elm)


3)  SEARCH FOR A NUMBER x IN THIS TUPLE
      numrs = (1, 4, 9, 16, 25, 36, 49, 64, 81, 100)

# USING WHILE LOOP:

x = 64

i = 0

while i < len(numrs):
if(numrs[i] == x):
print("Number found at idx", i)
i += 1



# USING FOR LOOP:


x = 49

idx = 0

for el in nums:
if(el == x):
print("Number found at idx", idx)
idx += 1

    


    
