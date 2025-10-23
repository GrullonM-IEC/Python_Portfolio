# Variables Prompts

## 1) Use the box model to explain what a variable is.  In your explanation, identify the two items every variable must have.
A variable is known as the code structure that is used to store data that will have a use later in the program. The box model is a way in order to store the data, each box is called a variable. The two items that every variable must include is a name and a value.
## 2) What types of data can be assigned to variables?
Any type of data can be assigned to a variable. Examples include integers, strings, floats, etc.
## 3) What is the assignment operator?
The assignment operator is known as the equal sign. It is how a value is able to be assigned to a variable. Whether it is changing the value of an already created variable or assigning a value to a brand new variable.
## 4) Write a line of code to assign the greeting, `Hello!` to the variable, `greeting`.
greeting = 'Hello!'
## 5) Explain what happens when a new value is assigned to a variable that already has a value assigned to it?
When a new value is assigned to a variable that has a value already assigned to it, the original value is changed to be the new value. The variable stays the same, it is only the value that changes.
## 6) Describe all requirements for a variable name to be legal in Python.
- Letter (uppercase and lowercase; underscores also count as letters)
- Numbers are allowed
- No other characters are allowed
- Numbers cannot go first
- No keywords
## 7) Provide several examples of legal variable names.
- First_value
- Second_part
- Line_1
- Section2
## 8) Provide several examples of variable names that are not legal.  Explain why each is not legal.
- 1One --> This is not legal due to the number being first, which is not allowed in variable names.
- My_Variable --> This one is not legal due to the spaces between the underscore. Python will not read that since it is not allowed
- Variable@Value --> This is not legal due to no other characters besides letters, numbers, and undrscores being allowed. @ is another character, meaning it is wrong.
## 9) Most often, what specific exception will be raised if you try to define a variable using a variable name that is not legal?
The specific exception will be switching up some of the characters in the name. Example: Makin one of the lowercase letters an uppercase and vice versa.
## 10) What are some examples of variable names that are legal but not recommended by the PEP 8 - Style Guide for Python Code.  Explain why each is not recommended.
- VariableName --> Not recommended due to confusion with typing it.
- ThisIsAVeryLongVariableName --> Not recommended due to the increased chance of an error happening when typing the name.
## 11) What will happen if you try to define a variable using a variable name that is legal but not recommended by the PEP 8 - Style Guide for Python Code?
The variable will be defined using the variable name. Issues would involve a decrease in reliablity when a code is functioning cause errors.
## 12)  The first code snippet below will generate an error, but the second code snippet below will not.  Explain why.

<pre><code>
print(greeting)
greeting = 'Hello'
</code></pre>

<pre><code>
greeting = 'Hello'
print(greeting)
</code></pre>

The first code would be an error due to the greeting not having an assigned value before being printed. A value is needed before printing, if not, then there would be nothing to print. It could end up with an error.
The second code would no be an error due to greeting value having an assigned value before printing. Since greeting was defined before printed, what was assigned to the variable be printed without any errors.
## 13)  What specific exception will be raised if Python tries to access a variable that has not yet been defined.
The exception would be an error, specifically a NameError. Since there is nothing that can be displayed since a variable is not defined, there would be no meaning to the name. It would cause a NameError and the code would not be able to function.
## 14) When the code segment below is executed, what will be displayed?  Code trace the code segment below in your notes, and insert a scan of your work below.
*To insert a scan of your work, save your scan as `LastNameFirstInitial_Intro_to_Variables_Code_Tracing.pdf`, upload it to your assignments folder, and copy/paste the URL of your scanned work into the <img> tag below.*

<img src = >

<pre><code>
x = 8
y = 3
x = x // y
y = x + y
print(x)
print(y)
</code></pre>
