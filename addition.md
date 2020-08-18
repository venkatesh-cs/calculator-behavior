# Addition

Scenario: Add 2 numbers
  
  Given : Calculator is turned on and we are not in any other calculation
  When : User enters in the following format: a + b =
  Then : Calculator displays the sum of the 2 numbers entered by the user
  
Scenario: User provides one operand and one operator
  
  Given : Calculator is turned on
  When :  User tries to add a number to nothing (For example, 10 + = )
  Then : Calculator assumes that 0 is added to the number.

Scenario: Addition of fraction

Given Calculator is turned on and is capable of handling fractions
when a user adds a fraction to a number
then display result in terms of fractions

Scenario: Addition of decimal

Given Calculator is turned on and is capable of handling decimals
when a user adds a decimal to another number (Not fraction)
then display result in terms of decimals

Scenario: Addition of decimal and fraction

Given calculator is turned on and is capable of handling
both decimals and fractions
-a when a user adds a decimal and fraction then display result in fraction
