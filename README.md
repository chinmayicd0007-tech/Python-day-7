# Python-day-7
My python practice
numbers = [45, 12, 89, 23, 67, 9]

# Assume the first element is both max and min
max_val = numbers[0]
min_val = numbers[0]

for num in numbers:
    if num > max_val:
        max_val = num
    if num < min_val:
        min_val = num

print("List:", numbers)
print("Maximum value:", max_val)
print("Minimum value:", min_val)
