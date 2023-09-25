# Writing Good Documentation

## Step 1- Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code. 
A good__Cloud__Engineer__ uses Codeblocks whenever possiable.

> Becasue it allows others to copy and paste their code to replicate or research issues.

```

def simple_generator(n):
    for i in range(n):
        yield i

# Using the generator
gen = simple_generator(5)
for num in gen:
    print(num)

```

```python
def simple_generator(n):
    for i in range(n):
        yield i

# Using the generator
gen = simple_generator(5)
for num in gen:
    print(num)
```

```bash
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
ValueError: This is a custom error message!
```
