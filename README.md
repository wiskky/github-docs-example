# Writing Good Documentation.

## Step 1 - Using Codeblocks.

Codeblock in **markdown** make it *very easy* for the tech people.

>`Becase` it allows to copy and paste their code to replicate or research issues.

This site was built using [GitHub Pages](https://pages.github.com/).

![This is the sample image](https://github.com/wiskky/github-docs-example/assets/19255446/3281e2e1-db67-43bc-a541-2bad64293d20)
<img width="200px" src="https://github.com/wiskky/github-docs-example/assets/19255446/3281e2e1-db67-43bc-a541-2bad64293d20" />
This is the Python code snipt

```python
def factorial(n):
    """Calculate the factorial of a non-negative integer."""
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)

# Test the function
number = 5
print(f"The factorial of {number} is {factorial(number)}")

```
