# Operators Prompts

## 1) Identify the two unary operators in Python.  Why are the referred to as 'unary'? What do they accomplish?
The unary + and - operators work on a single value which is why they are called unary, and simply indicate a number's sign or flip it.

## 2) Identify seven binary operators in Python.  Why are the referred to as 'binary'? What do they accomplish?
Binary operators like +, - *, /, //, %, and ** are called binary because they work on two values to perform mathematic operations.

## 3) Describe the results (including data type) when Python combines two ints using the `+`, `-`, `*`, `**`, and `//` operators.  Provide a few examples of each.
Whe Python combines two ints with +, -, *, **, and //, the result is always an int. ex. 3+2=5, 7-4=3, 6*3=18, 2**4=16, 9//2=4

## 4) Describe the result (including data type) when Python combines two ints using the `/` operator.  Consider examples in which one int **is** divisible by the other (e.g. `4/2`) as well as examples in which one int is **not** divisible by the other (e.g. `5/2`).  Provide a few examples of each.
Using / with two ints always gives a float, whether the division is even (4/2 = 2.0) or uneven (5/2 = 2.5, 7/3 = 2.333...)

## 5) Describe the result (including data type) when Python combines two ints using the `%` operator.
The % operator returns the remainder of dividing one int by another, and the result is always an int.

## 6) Describe the results (including data type) when Python combines two floats using the `+`, `-`, `*`, `**`, and `/` operators.  Provide a few examples of each.
When Python combines two floats with +, -, *, **, or /, it always produces a float result. ex. 1.5+2.5 = 4.0, 5.0-2.2 = 2.8, 2.0*3.5 = 7.0, 2.0**3.0 = 8.0, 7.5/2.5 = 3.0

## 7) Describe the result (including data type) when Python combines two floats using the `//` operator.  Consider examples in which one float **is** divisible by the other (e.g. `5.0//2.5`) as well as examples in which one int is **not** divisible by the other (e.g. `3.2//1.5`).  Provide a few examples of each.
When Python performs float division (//) with two floats, it returns a float representing the largest whole number value less than or equal to the true quotient. ex. 5.0//2.5 = 2.0, and 3.2//1.5 = 2.0

## 8) Describe the result (including data type) when Python combines two floats using the `%` operator.  Explain what happens if either float is not equivalent to int (e.g. `2.5`).  Provide a few examples of each.
Using % with two floats always produces a float the represents the remainder even when the numbers aren't whole, because Python still performs normal remainder math on decimal values. ex. 5.5%2.0 == 1.5, 7.0%3.5 == 0.0, 2.4%1.2 == 0.1

## 9) Describe the result (including data type) when Python combines an int and a float using the `+`, `-`, `*`, `**`, and `/` operators.  Provide a few examples of each.
When Python combines an int and a float using +, -, *, **, and /, it automatically converts the int to a float and produces a float result. ex. 3 + 2.0 = 5.0, 7 - 0.5 = 6.5, 4 * 1.5 = 6.0, 2 ** 3.0 = 8.0, and 9 / 2 = 4.5

## 10) Describe the result (including data type) when Python combines an int and a float using the `//` operator.  Consider examples in which one **is** divisible by the other (e.g. `6//1.5`) as well as examples in which one int is **not** divisible by the other (e.g. `4.0//3`).  Provide a few examples of each.
When an int and a float are combined with //, Python performs floor division and always returns a float, giving the largest whole-number value not greater than the true quotient. ex. 6//1.5 = 4.0, 4//3.0 = 1.0

## 11) Describe the result (including data type) when Python combines an int and a float using the `%` operator.  Explain what happens if the float is not equivalent to int (e.g. `3.5`).  Provide a few examples of each.
When Python applies the % operator to an int and a float, the result is always a float, and if the float is not an integer. ex. 3 % 3.5, 10 % 4.2, 7 % 1.6 

## 12) Describe the result (including data type) when Python combines two strings using the `+` operator.  Consider examples in which the strings contain non-numeric characters as well as examples in which the strings contain only numeric characters.  Provide a few examples of each.
When Python combines two strings using the + operator, it performs string concatenation and returns a new str regardless of whether the strings contain non-numeric characters. ex. "hello" + "world" --> "helloworld", "A" + "123" --> "A123" or only numeric characters. ex. "10" + "20" --> "1020", "3" + "7" --> "37"

## 13) Describe the result (including data type) when Python combines two strings using the `-`, `*`, `**`, `/`, `//`, and `%` operators.  Provide a few examples of each.
When Python combines two strings using -, **, /, //, or %, it raises a TypeError because these mathematic operators are not defined for str operands. ex. "a" - "b", "hello" / "world", "x" % "y", all errors, while * can only be used with a string and an integer, not two strings, so "a" * "b" also raises an error, though "hi" * 3 --> "hihihi" is valid.

## 14) Describe the result (including data type) when Python combines a string and a numeric data type using the `*` operator.  Consider examples in which the numeric data type is a int as well as examples in which the numeric data type is a float.  Additionally consider examples of the form `number * string` as well as examples of the form `string * number`.  Provide a few examples of each.
When Python combines a string and an int using the * operator, whether string * number or number * string, it performs string repetition and returns a str, ex. "hi" * 3 --> "hihihi", 2 * "ab" --> "abab", but using a float instead of an int in either prosition, ex. "hi" * 2.5 or 3.0 * "ab", raises a TypeError because Python requires the multiplier to be an integer.

## 15) Describe the result (including data type) when Python combines a string and a numeric data type using the `+`, `-`, `**`, `/`, `//`, and `%` operators.  Provide a few examples of each.
When Python combines a string and a numeric type using +, -, **, /, //, or %, it always raises a TypeError because these operations are not defined between str and numbers. ex. "hello" + 5, "abc" - 2, "x" ** 3, "text" / 2, "word" // 3, and "value" %4

## 16) Describe the result (including data type) when Python combines a boolean and a numeric data type using the `+`, `-`, `*`, `**`, `/`, `//`, and `%` operators.  Consider examples in which the numeric data type is an int as well as examples in which the numeric data type is a float.  Provide a few examples of each.
Booleans behave like integers, so combining a boolean with an int or float using +, -, *, **, /, //, or %, performs normal mathematic and returns a numeric result. ex. True + 5 --> 6, False * 8 --> 0, True ** 3 --> 1, False + 2.5 -->v2.5, True / 4 --> 0.25, False // 3 --> 0, True % 0.5 --> 0.0

## 17) Describe the result (including data type) when Python combines two booleans using the `+`, `-`, `*`, `**`, `/`, `//`, and `%` operators.  Provide a few examples of each.
Because Python treats booleans as integers, combining two booleans with +, -, *, **, /, //, or % performs normal mathematic and returns a numeric type. ex. True + False --> 1, True - True --> 0, True * False --> 0, False ** True --> 0, True / True --> 1.0, False // True --> 0, and True % False raises ZeroDivisionError since it attemps 1 % 0

## 18) Describe the result (including data type) when Python tries to divide, integer divide, or mod by `False`.  What happens and why?
False behaves like an integer 0, so dividing, integer dividing, or taking a modulus by False is the same as attempting the operation with zero, which raises a ZeroDivision because division by zero is undefined.
