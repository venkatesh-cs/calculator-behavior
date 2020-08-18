# Multiplication

Scenario: When any number (except infinity) is multiplied by 0

Given calculator is turned on
when a number other than infinity is multiplied by 0
then the result is 0

Scenario: When 0 is multiplied by any number

Given calculator is turned on
when 0 is multiplied by any number other than infinity
then the result is 0

Scenario: When a positive number is multiplied with a negative number

Given calculator is turned on
when a positive number is multiplied with a negative number
then the result is a negative number

Scenario: When a positive number is multiplied with a positive number

Given calculator is turned on
when a positive number is multiplied with a positive number
then the result is a positive number