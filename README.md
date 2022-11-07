enter the range you want to print
check if number is divisible by 3 and 5
if yes then print fizz buzz
if not then proceed to next step
check if number is divisible by 3
if yes then print fizz 
if not then proceed to next step
check if number is divisible by 5
if yes then print buzz
if not then proceed to next step
repeat the steps till the range is reached


for fizzbuzz in range(51):
    if fizzbuzz % 3 == 0 and fizzbuzz % 5 == 0:
        print("fizzbuzz")
        continue
    elif fizzbuzz % 3 == 0:
        print("fizz")
        continue
    elif fizzbuzz % 5 == 0:
        print("buzz")
        continue
    print(fizzbuzz)
