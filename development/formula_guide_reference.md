## Math Operators
| Operator | Description |
|---|---|
| + Add | Calculates the sum of two values. |
| - Subtract | Calculates the difference of two values. |
| * Multiply | Multiplies its values. |
| / Divide | Divides its values. |
| ^ Exponentiation | Raises a number to a power of a specified number. |
| ( ) Parenthesis | Specifies that the expressions within the parenthesis are evoluated first. All other experssions are evaluated using standard operator precedence. |

<br >

## Logical Operators
| Operator | Description |
|---|---|
| = and == Equals | Evaluates if two values are equivalent. |
| <> and != Not Equals | Evaluates if two are note equivalent. |
| < Less than | Evaluates if a value is less than the value that follows this symbol. |
| > Greater than | Evaluates if a value is greater than the value that follows this symbol. |
| <= Less than or Equals | Evaluates if a valur is less than or equals to the value that follows this symbol. |
| >= Greater than or Equals | Evaluates if a value is less than or equals to the value follow sthis symbol. |
| && AND | Evaluates if two values or expressions are both true. Use this operator as an alternative to the logical function AND.  |
| \|\| OR | Evaluates if at least one of multiple values or expressions is true. Use this operator as an alternative to the logical function OR. |

<br >

## Text Operators
| Operator | Description |
|---|---|
| & Concatenate | Connects two or more strings. |


<br >

## Date and Time Functions
| Function | Description |
|---|---|
| DATE | Returns a date value from year, month, and ay values you enter. Salesforce displays an error on the detailspage if the value of the DATE function in a formula field is an invalid date, such as February 29 in a non-leap year. |
| DATEVALUE | Returns a date value for a date/time or text expression. |
| DATETIMEVALUE | Returns a year, month, day and GMT time value. |
| DAY | Returns a day of the month in the form of a number between 1 and 31. |
| MONTH | Returns a month, a number between 1 (January) and 12 (December) in number format of a given date. |
| NOW | Returns a date/time representing the current moment. |
| TODAY | Returns the current date as a date data type. |
| YEAR | Returns the four-digit year in number format of a given date. |

<br >

## Informational Functions
| Function | Description |
|---|---|
| BLANKVALUE | Determines if an expression has a value and returns a substitute expression if it does not. If the expression has a value, return the value of the expression. |
| ISBLANK | Determines if an expression has a value TRUE if it does not. If it contains a value, this function returns FALSE. |
| ISNULL | Determines if an expression is null (blank) and returns TRUE if it is. If it contains a value, this function return FALSE. |
| NULLVALUE | Determines if an expression is (blank) and return a substitute expression if it is. If the expression is not blank, returns the value of the expression. |
| PRIORVALUE | Returns the previous value of a field. |

<br >

## Logical Functions
| Function | Description |
|---|---|
| AND | Return a TRUE response if all values are true; Returns a FALSE response if one or more values are false. |
| CASE | Checks a given expression against a series of values. If the expression is equal to a value, returns the corresponding result. If it is not equal to any values, it returns the else_result. |
| IF | Determines if expressions are true or false. Returns a given value if trueand another value if false. |
| ISCHANGED | Compares the value of a field to the previous value and returns TRUE if the values are different. If the values are the same, this function returns FALSE. |
| ISNEW | Checks if the formula is running during the creation of a new record and return TRUE if it is. If an existing record is being updated, this funcion returns FALSE. |
| ISNUMBER | Determines if a text value is a number and returns TRUE if it is. Otherwhise, it returns FALSE |
| NOT | Returns FALSE for TRUE, and TRUE for FALSE. |
| OR | Determines if expressions are true or false. Return TRUE if any expression is true. Returns FALSE if all expressions are false. |

<br >

## Math Functions
| Function | Description |
|---|---|
| ABS | Calculates the absolute value of a number. The absolute value of a number is the number without its positive or negative sign. |
| CEILING | Rounds a number up to the nearest integer. |
| DISTANCE | Calculates the distance between two locations in miles or kilometers. |
| EXP | Returns a value for e raised to the power of a number you specify. |
| FLOOR | Returns a number rounded down to the nearest integer. |
| GEOLOCATION | Returns a geolocation based on the provided latitude and longitude. Must be used with the DISTANCE function. |
| LN | Returns the natural logarithm of a specified number/ Natural logarithms are based on the constant e value of 2.71828182845904. |
| LOG | Returns the base 10 logarithms of a number. |
| MAX | Returns the highest number from a list of numbers. |
| MIN | Returns the lowest number from a list of numbers. |
| MOD | Returns a remainder after a number is divided by a specified divisor. |
| ROUND | Returns the nearest number to a number you specify, constraining the new number by a specified number of digits. |
| SQRT | Return the positive square root of a given number. |

<br >

## Text Functions
| Function | Description |
|---|---|
| BEGINS | Determines if text begins with specific characters and returns TRUE if it does. Return FALSE if it does not |
| BR | Inserts a line break in a string of text. |
| CASESAFEIF | Converts a 15-characte ID to a case-insensitive 18-character ID. |
| CONTAINS | Compares two arguments of text and returns TRUE if the first argument contains the second argument. If not, return FALSE. |
| FIND | Returns the position of a string within a string of text represented as a number. |
| GETSESSIONID | Returns the user's session ID. |
| HYPERLINK | Creates a link to a URL specified that is linkable from the text specified. |
| IMAGE | Inserts an image with alternate text and height/width specifications. |
| INCLUDES | Determines if any value selected in a mult-select picklist field equals a text literal you specify. |
| ISPICKVAL | Determines if the claues of a picklist field is equal to a text literal you specify. |
| LEFT | Returns the specified number of characteres from the beginning of a text string. |
| LEN | Returns the number of characters in a specified text string. |
| LOWER | Converts all letters in the specified text string to lowercase. Not letters are unaffected by this function. Locale rules are applied if a locale is provided. |
| LPAD | Inserts characters you specify to the left-side of a text string. |
| MID | Returns the specified number of characters from the middle of a text string given the starting position. |
| RIGHT | Returns the specified number of characters from the end of a text string. |
| RPAD | Inserts characters you specify to the right-side of a text string. |
| SUBSTITUTE | Substitutes new text for old text in a text string. |
| TEXT | Converts a percent, number, date, date/time, or currency type field into text anywhere formulas are used. Also, converts picklist values to text in validation rules, formula fields, and field updates. |
| TRIM | Removes the space and tabs from the beginnig and end of a text string. |
| UPPER | Converts all letters in the specified text string to uppercase. Not letters are unaffected by this function. Locale rules are applied if a locale is provided. |
| VALUE | Converts a text string to anumber. |

<br >

## Summary Functions
`The following functions are available with summary, matrix, and joined reports.`
| Function | Description |
|---|---|
| PARENTGROUPVAL | This function returns the value of a specified parent grouping. A "parent" grouping is any level above the one containing the formula. You can only use this function in custom summary formulas for report. |
| PREVGROUPVAL | This function returns the value of a specified previous grouping. A "previous" grouping is one that comes before the current grouping in the report. Choose the grouping level and increment. The increment is the number of columns or rows before the current summary. The default is 1; the maximum is 12. You can only use this function in custom summary formulas for reports |

<br >

## Advanced Functions
| Function | Description |
|---|---|
| GETRECORDIDS | Returns an array of strings in the form of record IDs for the selected records in a list, such as a list view or related list. |
| INCLUDE | Returns content from an s-control snippet. Use this function to reuse common code on many s-controls. |
| LINKTO | Return a relative URL in the form of a link (href and anchor tags) for a custom s-control or Salesforce page. |
| REGEX | Compares a text field to a regular expression and returns TRUE if there is a match. Otherwise, it returns FALSE. A regular expression is a string used to describe a format of string according to certain syntax rules. |
| REQUIRESCRIPT | Returns a script tag with source for a URL yo uspecify. Use this function when referencing the force.com AJAX Toolkit or other Javascript toolkits. |
| URLFOR | Returns a relative URL for an action, s-control, Visualforce page, or a file in s static resource archive in a Visualforce page. |
| VLOOKUP | Returns a value by looking up a related value on a custom object similar to the VLOOKUP() Excel function. |

<br >

## Encoding Functions
| Function | Description |
|---|---|
| HTMLENCODE | Encodes text and merge field values for use in HTML by replacing characters that are reserved in HTML, such as the greater-than sign (>), with HTML entity equivalents, such as \&gt;. |
| JSENCODE | Encodes text and merge field values for use in JavaScript by inserting escape characters, such as a backslash (\\), before unsafe JavaScript characters, such as the apostrophe ('). |
| JSINHTMLENCODE | Encodes text and merge field values for use in JavaScript within HTML tags by inserting escape characters before unsafe JavaScript characters and JSINHTMLENCODE replacing characters that are reserved in HTML with HTML entity equivalents. |
| URLENCODE | Encodes text and merge field values for use in URLs by replacing characters that are illegal in URLs, such as blank spaces, with the code that represent URLENCODE those characters as defined in RFC 3986, Uniform Resource Identifier (URI): Generic Syntax. For example, blank spaces are replaced with %20, and exclamation points are replaced with %21. |