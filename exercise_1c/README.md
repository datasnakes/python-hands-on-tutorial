# Exercise 1c - Understanding Python Using R and RStudio

## Objectives

- Learn how to install the RStudio IDE (like Pycharm or Anaconda for R)
- Learn how to install or upgrade R
- Learn how to install R packages with utils and devtools (like pip but in the R shell)
- Learn more about [Markdown with RStudio](https://rmarkdown.rstudio.com/)

## Practice

In a folder named `exercise_1c`, create a `README.md` file and add the below to it.

- Create a markdown table
- Add a photo of the python language logo to a readme

### Code from Teletyping Session for exercise_1c

To learn the knowledge from [Good Python code](teletyping.py).


```python
# x is a variable
# it's type is an integer
x = 5
y = 2 * x

# you can add integers together like a normal math equation
z = 2 * (y + x)

# print() is a function
# functions always have parentheses
print(y)
print(z)

# a, b, and c are also variables
# Their types are strings
a = 'xiao'
b = 'rob'
c = "shaurita"
d = "snack"
number = 999
space = " "


# You can also add strings together
e = a + space + b + space + c + space + d

# Formatted strings
f = f""
formatted_string = f"{a} {b} {c} {d} {number}"
sentence = "I am teletyping with {}, {}, and {}, but I want a {}.".format(a, b, c, d)
print(e)
print(formatted_string)
print(sentence)

# a-d are variables
# They are types of strings
a = "tiger"
b = "monkey"
c = "lion"
d = "bear"

# add strings together
e = a + 2 * space + b + space + c + 2*space
print(e)

#def print(items):
#    send_as_output(items)

def get_popular_genes(type):
    print(type)

get_popular_genes(type="GPCR")

# Math symbols
# * == multiply
# / == divide
# - == subtract
# + == addition

# print() - is the most popular and important python functions
# list()
# dict()
# dir()
```

***

[Previous](../exercise_1b/README.md) | [Next](../exercise_2/README.md) | [List of contents](../README.md#exercises)
