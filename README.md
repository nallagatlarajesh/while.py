# while.py
#find the sum of all positiive numbers enterd by the user till user enters a nehgatuive number
entry=0
sum1=0
print("enter the numbers to find their sum,negative number ends the loop")
while True:
    entry=int(input())
    if (entry<0):
        break
    sum1+=entry
print("sum=",sum1)
