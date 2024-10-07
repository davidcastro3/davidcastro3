
num1=int(input("enter num1:"))
num2=int(input("enter num2:"))
action=str(input("choose action: add(a), sub(s) mult(m) div(d)->"))

print("the resultis "",end=")
if action == "a":print(num1+num2)
elif action == "s":print(num1-num2)
elif action == "m":print(num1*num2)
else:print(num1/num2)

