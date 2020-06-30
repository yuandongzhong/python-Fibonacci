# python-Fibonacci
An elegant Fibonacci algorithm for Python


## What is Fibonacci
The Fibonacci Sequence follows one rule: get the next number in the sequence by adding the two previous numbers. Here is an example of the sequence:
```
0,1,1,2,3,5,8,13,21,34...
```
Step through each value. You start with 0 and 1. 0 + 1 = 1, so you add 1 to the sequence. 1 + 1 = 2, so 2 is added. 1 + 2 = 3, so 3. 2 + 3 = 5, et cetera. 

You could represent these numbers as Python list, and it would look something like this:

```
fib_seq = []
fib_seq[0] = 0
fib_seq[1] = 1
fib_seq[2] = 1
fib_seq[3] = 2
fib_seq[4] = 3
fib_seq[5] = 5
fib_seq[6] = 8
fib_seq[7] = 13
fib_seq[8] = 21
fib_seq[9] = 34
```

## Algorithmn in Python
Isn't this elegant?
```
def get_fib(position):
    if position == 0 or position == 1:
        return position
    return get_fib(position - 1) + get_fib(position - 2)
```
