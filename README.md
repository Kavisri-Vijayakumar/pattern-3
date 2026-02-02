# pattern-3
s=input("enter the string : ")
n=len(s)
for i in range(0,n):
    for j in range(0,i):
        print(s[j],end='')
    print("")

Output
enter the string : kavisri

k
ka
kav
kavi
kavis
kavisr
