# computing-avg-of-several-integers-56-100
count = int(input("Enter the count of numbers: "))

total = 0
for i in range(count):
    x = int(input("Enter an integer: "))
    total = total + x

avg = total / count
print("The average is:", avg)
