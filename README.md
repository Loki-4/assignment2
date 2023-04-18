# assignment2
a=int(input("enter no of subject: "))
sum=0
for i in range(1,a+1):
  b=int(input("enter "))
  sum+=b
avg=sum/a
if avg>=90 :
 print("A grade")
elif avg>=70 and avg<90 :
  print("B grade")
elif avg>=40 and avg<70 :
  print("C grade") 
else:
  print("D grade")
