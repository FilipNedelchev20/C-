You are given a list of integers in one line. Randomize their order and print each number at a separate line.

Hints:
 Split the input string by (space) and create an array of integers.
 Create a random number generator – an object rnd of type Random.
 In a for‐loop exchange each number at positions 0, 1, ... numbers.Length‐1 by a number at random
position. To generate a random number in range use rnd.Next(minValue, maxValue). Note that by
definition minValue is inclusive, but maxValue is exclusive.
 Print each number in the array on new line.
 Learn more about how to shuffle an array at: https://en.wikipedia.org/wiki/Fisher%E2%80%93Yates_shuffle
