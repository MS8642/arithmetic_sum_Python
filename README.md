# arithmetic_sum_Python
# Simple program that performs an arithmetic sum of 10 numbers

num_terms = 10

sum = 0
for i in range(1, num_terms + 1):
    sum = sum + i

print("Arithemtic Sum for numbers from 1 to",num_terms,"is",sum)

# How it works
# The task is to sum up 10 terms.
# The use of range() function will help to get through the number of terms it is required to sum.
# The "sum" variable starts at zero since that will be the starting point for summing
# The zero will sum up with the first number ( 1) and the new sum will be saved in the
# sum variable which will consequently be used in the summation of other terms.

# Note: It is possible to update this code to request a number of terms required to sum
# from the user.
