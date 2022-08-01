# Python Introduction
###
### Python Operators
###
#### Two types of Operators
##### Arithmetic Operators
- `+ - * /`
- `+` adds two operands (variables)
- `-` subtracts
- `*` multiply
- `/` divide
- `**` exponent
- `%` returns remainder
##### Comparison Operators 
- `>` greater than
- `<` less than
- `==` is equal to
- `!=` not equal to
- `>=` greater than or equal to
- `<=` less than or equal to
##### Builtin Python Functions
```python
a = 7
b = 2
print(a)
print(b)
print(a > b)
print(a < b)
print(a == b)
print(a != b)

print(a % 2)

greeting = "HelloWorld"

# what options are available in python's builtin library
print(greeting)
print(greeting.isalpha())
print(greeting.islower())
print(greeting.isdigit())
print(greeting.__contains__("Hello"))
print(greeting.endswith("d"))
```
##### String Concatenation Casting

Index in Python starts with 0.
####
```python
greeting = "Hello World!"
print(len(greeting))
print(greeting[4:])
print(greeting[:-7:-1])
print(greeting[:6])
```
##### More String functions
```python
example_string = "james         "
print(len(example_string))  # returns 14
print(len(example_string.strip(" ")))  # returns 5

print(example_string.capitalize())  # returns James
print(example_string.count("a"))

example_text = "here's some text With lots of text"
print(example_text.lower().capitalize())
print(example_text)

print(example_text.replace("With", ","))
```