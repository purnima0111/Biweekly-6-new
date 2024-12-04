# Biweekly-6-new
# Program to find the largest number in a list

# Function to find the largest number
def find_largest(numbers):
    largest = numbers[0]
    for num in numbers:
        if num > largest:
            largest = num
    return largest

# List of numbers
nums = [15, 42, 7, 89, 33]

# Find and display the largest number
print("The largest number is:", find_largest(nums))
