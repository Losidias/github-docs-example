# Writing good documentation

## Step 1 - Using Codeblocks

Codeblocks in markdown make it *very easy* for tech people to **copy, plaste, share** code.  
A good __Cloud Engineer__ uses Codeblocks whenver possible.

Because it allows others to copy and past their code to replicate or research issues.

- In order to create codeblocks in markdown, you need to use three backticks ```
- Not to be confused with single quotation '''
<br />
<br />

with backticks (correct method)

```
# This is a simple Python function that adds two numbers
def add_numbers(a, b):
    return a + b

# Call the function and print the result
result = add_numbers(3, 4)
print(f"The sum is: {result}")
```
<br />
<br />
- When you can, you should attempt to apply syntax highlighting to your codeblocks.

 ```python
# This is a simple Python function that adds two numbers
def add_numbers(a, b):
    return a + b

# Call the function and print the result
result = add_numbers(3, 4)
print(f"The sum is: {result}")
```

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.
<br />
<br />
Example Error message

```bash
Traceback (most recent call last):
  File "example.py", line 3, in <module>
    result = add_numbers(3, 'four')
TypeError: unsupported operand type(s) for +: 'int' and 'str'
```
> Here is an example of using a codeblock for an errors that appears in bash.
<br />
<br />


![giphy-1765870156](https://github.com/Losidias/github-docs-example/assets/11257906/40bbe964-5984-4c16-bc30-374c60137aac)
> Example of embedding images into markdown.

## References


- [cmark-gfm](https://github.com/github/cmark-gfm)<sup>1</sup>
- [Basic writing and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)<sup>2</sup>
