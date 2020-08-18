# Subtraction

Scenario: Subtract a number from 0

Given calculator is turned on and it is capable of handling negative numbers
when a user subtracts a number from 0
then the result is equal to (-1 * number)

Scenario: Subtract a positive number from a negative number

Given calculator is turned on and it is capable of handling negative numbers
when a user subtracts a positive number from a negative number
then the result is a negative number
