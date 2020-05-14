#1)

ls=[]

no = int(input("enter number"))

count =0

while no != 0:

    no = no//10
    
    count = count+1
    
for i in range(1,count+1):

    s=i*10
    
    ls.append(s)
    
    rev=ls[::-1]
        
print(rev)


#2)

s1 = input("Enter 1st String")

s2 = input("Enter 2nd String")

l1=len(s1)

mid =l1//2

print(s1[0:mid]+s2+s1[mid:])


#3)

s1 = input("enter a String")

s2=  s1.split()

Small = []

Caps = []

for i in s1:

    if i.isupper():
    
        Caps+=i
        
    else:
    
        Small+=i

print(''.join(Small+Caps))


#4)

s1 = "Eng = 85 Sci = 65 Math = 68"

s2 = s1.split()

s3 = []

for i in s2:

    if i.isdigit():
    
        s3.append(i)
        
print(s3)        
       
        
        
        
        

#5)

list1 = []

list2 = []

even = []

odd = []

list3= []

N = int(input("Number of element"))

for i in range(0,N):

    N1 = int(input("Enter Number in List1:-"))
    
    list1.append(N1)
    
    N2 = int(input("Enter Number in List2:-"))
    
    list2.append(N2)

for i in list1:

    if i%2!=0:
    
        odd.append(i)
        
for i in list2:

    if i%2==0:
    
        even.append(i)

print(even)

print(odd)

list3 = odd+even

print(list3)





      
