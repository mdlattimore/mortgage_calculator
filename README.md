# Mortgage Calculator

This is a terminal-based program for amortizing and displaying loan payment information.
The program takes user input for loan amount, interest rate, 
loan term (in months) and optionally, homeowners insurance and property tax 
amounts, calculates both the principal and interest payment amount and total 
payment amount (if amounts for taxes and insurance are provided) and displays 
the result in a terminal panel. Further, the user is given the option to view a full 
amortization schedule and, if they chose to do so, are given the further option 
to save the amortization table (which is saved as a text file).  
    
The module uses the 'rich' library to format the output to the terminal, allowing
easy customization of the presentation. In particular, the module uses the Table and 
Panel classes from the rich.console module. The mathematical calculations are 
handled by a scratch-written amortization function saved as separate module. 
There are very good amortization libraries in Pypi. However, I decided to write 
my own function to decrease the number of dependencies. See also the cli version in 
a separate repository.