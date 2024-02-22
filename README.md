# Author: Michelle Frugia
# GitHub username: frugiam
# Date: 02/21/2024
# Description: Project 7b

def reverse_list(my_list):
    # Get the length of the list
    length = len(my_list)

    # Iterate through half of the list and swap elements
    for i in range(length // 2):
        # Swap elements at indices i and length - 1 - i
        my_list[i], my_list[length - 1 - i] = my_list[length - 1 - i], my_list[i]
