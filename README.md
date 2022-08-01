# User Details Task
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
## Strings
### String Indexing

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
print(example_text.lower().capitalize())  # converts to lower case then capitalizes the string
print(example_text)

print(example_text.replace("With", ","))
```
### String Concenatration
```python
first_name = "James"
last_name = "Bond"
middle_name = "007"
age = 47
print(f"{first_name} {middle_name} {last_name} {age}")
print(first_name + " " + middle_name + " " + last_name + " " + str(age))
```
### .gitignore
- Create a text file in the root directory, and add the files that you wish to be ignored to it as follows.
![image](https://user-images.githubusercontent.com/110126036/182197546-413828be-18b9-412a-abd6-6d119de7e411.png)

###
## Definition of Ready 
- Create a new repo called user_details
- create a new project in pycharm for this task
- add a README.md for this task with complete documentation
- explain how to create a .gitignore file in your pycharm
- explain string concatenation 
- ignore any dependencies not required to be pushed to github

## Definition of Done
- Video presenting the above.
- Github page documentation also describing the above.
