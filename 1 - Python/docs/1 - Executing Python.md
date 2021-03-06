

# Running Python via the CLI

## Using the Python Interactive Interpreter

Open a terminal and type `python`, you should see a welcome message, and be left with `>>>`. Try typing in the following commands.

```
>>> 5 + 3
8
>>> 4*(5+1)+8
32
```

We can let names stand for values, like in algebra.

```
>>> x = 5
>>> x = x + 3
>>> x
8
```

To exit the python interpreter, type `exit()` or `quit()`


## Executing Python Source Files

You can execute python code saved in a plain text file by typing `python filename`. Create a new file `temp.py` with the following contents:

```
x = 5
x = x + 3
print(x)
```

Execute this file by opening a terminal, and type `python temp.py`. You should see `8` as the output. Every time you edit the source file, you then run it by typing `python filename` again.