# Random-Number-Generator
Generate random numbers in the specified range.
import random

def generate_random_numbers(count, start_range, end_range):
    return [random.randint(start_range, end_range) for _ in range(count)]

num_count = int(input("Enter the number of random numbers: "))
start_range = int(input("Enter the start range: "))
end_range = int(input("Enter the end range: "))
random_numbers = generate_random_numbers(num_count, start_range, end_range)
print("Random Numbers:", random_numbers)
