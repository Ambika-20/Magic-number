# Magic-number
num = int(input("Enter a num:"))
x = num
while x >= 10:
    sum = 0
    while x>0:
        sum = x%10
        x = x//10
    x = sum
if sum == 1:
    print("Given number is Magic Number:")
else:
    print("Given number is not a Magic Number:")
