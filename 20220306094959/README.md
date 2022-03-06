# Anonymous Functions:

**Anonymous functions** also known as **Lambda functions** in python are
pretty powerful as you can declare an entire function in a single
line though it does reduce the readability of the code.

**Syntax for lambda functions:**

```python

# <variableName> = lambda <input1> <input..n> : <return val1>, <return val2>
# To call the anonymous function we use the following ...
# variableName(parameter1, parameter..n)
a = lambda x: x*2
print(a(2))

```
**Output:**

> 4

## When to use lambda functions?

The best place to use lambda functions are when you require to do
something mathematical or when you require a function which you are
going to use much just for a couple times maybe that's when you should
use lambda functions. You can even combine two functions and pass them
to a single lambda function and call both of them at once.

**Here is a small example of the same:**

``` python

n = int(input("Enter a number: "));

def compose(f,g):
    return lambda x: f(g(x))

def double(x):
    return x*2;

def inc(x):
    return x+1;

# The Function will take n as input increment it by 1 then find its
# square.
compositor = compose(double, inc)
print(compositor(n))

```

# Tags:

    #python #lambda #functions #anonymous
