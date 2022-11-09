Read a list of integers and print them in ascending order, along with their number of occurrences.

Hints:
Read an array of doubles:
Use SortedDictionary<double, int> named counts.
Pass through each of the numbers and increase their count ‐ counts[num], if num exists in the dictionary, or assign
counts[num] = 1, if the number does not exist in the dictionary. We are assigning it that
value, beacause it is its first occurance. The count represents the occurances.
Pass through all of the numbers in the dictionary and print the number num and its count of occurrences.
