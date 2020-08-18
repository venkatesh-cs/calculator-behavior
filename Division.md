# Division

Scenario: Divide a number by 0
Given Calculator is turned on
When user tries to divide a number (not infinity) by 0
Then Calculator displays a message saying that it is an invalid operation

Scenario: Divide a Positive number by a negative number

Given calculator is turned on and is capable of handling negative numbers
When user divides a positive number by a negative number (or vice versa)
then the result is a negative number

Scenario: Divide a Positive number by a positive number

Given calculator is turned on
When user divides a positive number by a positive number
then the result is a positive number

Scenario: Divide a Negative number by a negative number

Given calculator is turned on and is capable of handling negative numbers
When a user divides a negative number by a negative number
then the result is a negative number

Scenario: Divide fraction by another fraction

Given calculator is turned on and is capable of taking input
in terms of fractions
when user divides a fraction by a number
then result should be a fraction
