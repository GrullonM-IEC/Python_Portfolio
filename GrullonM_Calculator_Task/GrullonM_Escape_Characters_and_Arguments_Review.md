# Escape Characters and Arguments Prompts

## 1) Explain what escape characters are and in general what they accomplish.
Escape characters are shortcuts that let you include special things like new lines, tabs, or quotes inside a string.

## 2) What symbol do escape characters begin with?
Escape characters begin with the backslash symbol \.

## 3) Provide three examples of escape characters and explain what each accomplishes.
\n - creates new line.
\t - inserts a tab space.
\' allows you to include a single quote inside a string.

## 4) Describe two different strategies for displaying `'` or `"`.
You can show ' and " in a string by using the opposite kind of quotes around the text or by escaping the quote with a backslash.

## 5) Explain the difference between the positional argument passing technique and the keyword argument passing technique.
Positional arguments are passed to a function in the exact order the parameters are defined, while keyword arguments specify each parameter by name so order doesn't matter.

## 6) In the `print()` function, which arguments are passed using the positional technique?
In the print() function, the values you want to display are passed as positional arguments. ex. print("Hello", 5, name)

## 7) In the `print()` function, which arguments are passed using the keyword technique?
In the print() function, the optional settings, such as sep, and end, are passed using the keyword argument technique.

## 8) When the `print()` function recieves several objects as positional arguments, how does it respond?
When print() gets multiple positional arguments, it shows them all in order with a space between them by default.

## 9) Explain what the `sep` parameter accomplishes.
The sep parameter lets you choose what separator goes between those objects when they are printed.

## 10) Explain what the `end` parameter accomplishes.
The end parameter controls what is printed after the final item, with the default being a new line.
