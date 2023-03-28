## Math Operators
| Operator | Description |
|---|---|
| + Add | Calculates the sum of two values |
| - Subtract | Calculates the difference of two values |
| * Multiply | Multiplies its values |
| / Divide | Divides its values |
| ^ Exponentiation | Raises a number to a power of a specified number |
| ( ) Parenthesis | Specifies that the expressions within the parenthesis are evoluated first. All other experssions are evaluated using standard operator precedence |

<br >

## Logical Operators
| Operator | Description |
|---|---|
| = and == Equals | Evaluates if two values are equivalent |
| <> and != Not Equals | Evaluates if two are note equivalent |
| < Less than | Evaluates if a value is less than the value that follows this symbol |
| > Greater than | Evaluates if a value is greater than the value that follows this symbol |
| <= Less than or Equals | Evaluates if a valur is less than or equals to the value that follows this symbol |
| >= Greater than or Equals | Evaluates if a value is less than or equals to the value follow sthis symbol |
| && AND | Evaluates if two values or expressions are both true. Use this operator as an alternative to the logical function AND  |
| \|\| OR | Evaluates if at least one of multiple values or expressions is true. Use this operator as an alternative to the logical function OR |

<br >

## Text Operators
| Operator | Description |
|---|---|
| & Concatenate | Connects two or more strings |


<br >

## Date and Time Functions
| Function | Description |
|---|---|
| DATE | Returns a date value from year, month, and ay values you enter. Salesforce displays an error on the detailspage if the value of the DATE function in a formula field is an invalid date, such as February 29 in a non-leap year |
| DATEVALUE | Returns a date value for a date/time or text expression |
| DATETIMEVALUE | Returns a year, month, day and GMT time value |
| DAY | Returns a day of the month in the form of a number between 1 and 31 |
| MONTH | Returns a month, a number between 1 (January) and 12 (December) in number format of a given date |
| NOW | Returns a date/time representing the current moment |
| TODAY | Returns the current date as a date data type |
| YEAR | Returns the four-digit year in number format of a given date |

<br >

## Informational Functions
| Function | Description |
|---|---|
| BLANKVALUE | Determines if an expression has a value and returns a substitute expression if it does not. If the expression has a value, return the value of the expression |
| ISBLANK | Determines if an expression has a value TRUE if it does not. If it contains a value, this function returns FALSE |
| ISNULL | Determines if an expression is null (blank) and returns TRUE if it is. If it contains a value, this function return FALSE |
| NULLVALUE | Determines if an expression is (blank) and return a substitute expression if it is. If the expression is not blank, returns the value of the expression |
| PRIORVALUE | Returns the previous value of a field |

<br >

## Logical Functions
| Function | Description |
|---|---|
| AND | Return a TRUE response if all values are true; Returns a FALSE response if one or more values are false |
| CASE | Checks a given expression against a series of values. If the expression is equal to a value, returns the corresponding result. If it is not equal to any values, it returns the else_result |
| IF | Determines if expressions are true or false. Returns a given value if trueand another value if false |
| ISCHANGED | Compares the value of a field to the previous value and returns TRUE if the values are different. If the values are the same, this function returns FALSE |
| ISNEW | Checks if the formula is running during the creation of a new record and return TRUE if it is. If an existing record is being updated, this funcion returns FALSE |
| ISNUMBER | Determines if a text value is a number and returns TRUE if it is. Otherwhise, it returns FALSE |
| NOT | Returns FALSE for TRUE, and TRUE for FALSE |
| OR | Determines if expressions are true or false. Return TRUE if any expression is true. Returns FALSE if all expressions are false |

<br >

## Math Functions
| Function | Description |
|---|---|
| ABS | Calculates the absolute value of a number. The absolute value of a number is the number without its positive or negative sign |
| CEILING | Rounds a number up to the nearest integer |
| DISTANCE | Calculates the distance between two locations in miles or kilometers |
| EXP | Returns a value for e raised to the power of a number you specify |
| FLOOR | Returns a number rounded down to the nearest integer |
| GEOLOCATION | Returns a geolocation based on the provided latitude and longitude. Must be used with the DISTANCE function |
| LN | Returns the natural logarithm of a specified number/ Natural logarithms are based on the constant e value of 2.71828182845904 |
| LOG | Returns the base 10 logarithms of a number |
| MAX | Returns the highest number from a list of numbers |
| MIN | Returns the lowest number from a list of numbers |
| MOD | Returns a remainder after a number is divided by a specified divisor |
| ROUND | Returns the nearest number to a number you specify, constraining the new number by a specified number of digits |
| SQRT | Return the positive square root of a given number |