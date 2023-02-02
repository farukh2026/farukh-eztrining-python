'''l=[1,2,34,5,6,76,7,78,87,78,78,787,87,'sam','manoj']
print(l[::-1])
print(l[2::-1])
print(l[:2:-1])
print(l[1:6:-1])
print(l[-6:-1])
print(l.count(78))#count the particular number 3
l.append(90)
l.insert(1,76)
l.pop(2)
print(l)
l.clear()
print(l)
#create a list with 10items print one by one
#create a list with floet , find and display sum and average of list
#after create a list with 6 elements from user, extract only even and print
l1=[]
for i in range(1,11):
    l1.append(i)
    print(l1[i-1])
    i+=1
#=========================================
n=int(input("enter the size of list"))
l2=list(map(float,input("enter the floats").strip().split()))[:n]
sum=0
avg=0
for i in range(len(l2)):
    sum+=l2[i]
avg=sum/n
print("sum: ",sum,"average: ",avg) 
#===========================================
n1=int(input("enter the size of list"))
l3=list(map(int,input("enter the numbers").strip().split()))[:n1]
for i in range(n1):
    if l3[i]%2==0:
        print(l3[i])
#============================================'''
n=int(input("size of list: "))
l4=list(map(int,input("enter the numbers").strip().split()))[:n]
print("list is : ", l4)
sum=int()
for i in range(len(l4)):
    s=l4[i]*l4[i]
    s1=str(s)
    sum=0
    for j in range(len(s1)):
       l=int(s1[j])
       sum=sum+l
    if sum==l4[i]:
        print(l4[i],"is neon number")
    else:
        print(l4[i],"is not a neon number")
       