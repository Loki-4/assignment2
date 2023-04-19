# assignment2
a=int(input("enter no of subject: "))
sum=0
for i in range(1,a+1):
  b=int(input("enter "))
  sum+=b
avg=sum/a
if avg>=90 and avg<=100:
 print("A grade")
elif avg>=70 and avg<90 :
  print("B grade")
elif avg>=40 and avg<70 :
  print("C grade") 
else:
  print("D grade")


password=input("enter: ")
rule = "abcdefghijklmnopqrstuvwxyzABCDEFGHIJKLMNOPQRSTUVWXYZ1234567890"
u=l=d=special=0
le=len(password)
for i in password:
  if i.isdigit():
    d =1
  if i.isupper():
    u =1
  if i.islower():
    l = 1
  if char not in chars :
    special = 1
if l and special and u and d and le==10:
  print("Password is strong and enough")
elif d and l or le==10:
  print("Password is need to change")
else :
  print("Password is too weak")


