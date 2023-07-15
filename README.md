# Roman-to-Integer

This code provides a solution to the problem of converting a Roman numeral string to its corresponding integer value.

## Problem Description

Given a Roman numeral as a string, the code converts it to an integer. The Roman numeral consists of seven different symbols: I, V, X, L, C, D, and M. Each symbol has a specific value: I = 1, V = 5, X = 10, L = 50, C = 100, D = 500, and M = 1000.

The Roman numerals are usually written from largest to smallest, and there are specific cases where subtraction is used to represent numbers. For example, IV represents 4 (5 - 1) and IX represents 9 (10 - 1). The code takes into account these special cases while converting the Roman numeral to an integer.

## Implementation

The code is implemented as a C++ class named `Solution`. It provides a member function `romanToInt` that takes a string `s` representing the Roman numeral and returns the corresponding integer value.

The implementation follows the following steps:

1. Initialize a variable `result` to store the final integer value.
2. Iterate over the Roman numeral string from left to right.
3. Use a switch-case statement to evaluate the value of each Roman numeral character based on its position and the following character, if applicable.
4. Update the `result` based on the evaluated value of the Roman numeral character.
5. Return the final `result` as the integer value.

## Usage

1. Create an instance of the `Solution` class.
2. Call the `romanToInt` function on the instance, passing the Roman numeral string as an argument.
3. The function returns the corresponding integer value.
