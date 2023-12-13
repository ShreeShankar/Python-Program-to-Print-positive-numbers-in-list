# Python-Program-to-Print-positive-numbers-in-list
My captain Project Submission 2
def print_positive_numbers(input_list):
    positive_numbers = [num for num in input_list if num > 0]
    print("Input:", input_list)
    print("Output:", positive_numbers)

# Example usage:
list1 = [12, -7, 5, 64, -14]
list2 = [12, 14, -95, 3]

print_positive_numbers(list1)
print_positive_numbers(list2)

