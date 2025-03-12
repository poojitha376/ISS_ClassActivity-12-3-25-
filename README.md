# ISS_ClassActivity-12-3-25-

Syntax Errors Fixed:

Added missing colons (:) in function definitions and loops.
def is_narc(n):
def print_narcis_numbers(start, end):
for num in range(start, end + 1):
Required for proper function and loop syntax.

Fixed Variable Assignment Errors:

Used = instead of == for assignments.
wrong : num_str == str(n) → right : num_str = str(n)
wrong : num_digits == len(num_str) → right : num_digits = len(num_str)
== is for comparison, = is for assignment.

Fixed Incorrect Operator for Exponentiation:

wrong : sum(int(digit) *** num_digits for digit in num_str)
right : sum(int(digit) ** num_digits for digit in num_str)
*** is invalid; ** is the correct exponentiation operator.

Fixed Incorrect Function Name in Condition:

wrong : if is_narcissistic(num)
right : if is_narc(num)
is_narcissistic() was incorrect; it should match the defined function.

Fixed Function Call with Missing Comma:

wrong : def print_narcis_numbers(start end)
right : def print_narcis_numbers(start, end)
Function parameters must be separated by a comma.

Corrected Function Name in the Final Call:

wrong : print_narc_numbers(1000, 5000)
right : print_narcis_numbers(1000, 5000)
The function name was inconsistent with its definition.


These fixes corrected syntax errors, incorrect operators, function mismatches, and improper assignments, ensuring that the script runs correctly without errors.
