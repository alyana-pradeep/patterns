# patterns
for i in range(1,6+1): #NUMBER PATTERN IN TRIANGLE
    for j in range(6-i):
        print(" ",end="")
    for k in range(i):
        print(i,end=" ")
        i+=1
    print()

for i in range(1,6+1):  #TRIANGLE
    for j in range(6-i):
        print(" ",end="")
    for k in range(i):
        print("*",end=" ")
    print()
