## Welcome to my GitHub.io Page

My name is Joseph, and I work for [Techsquare](http://www.techsquare.com/) at the [Massachusetts Green High Performance Computing Center](https://www.mghpcc.org/).

I got this job during the summer of 2021, and started that September.

### What I'm Doing

Currently I am working through a list of training exercises to make sure I am up to par with what will be required of me in the job, and building this website is one of those items!

### A code sample of a Fibonacci number generator:

```markdown
# Define the fibonacci function
def fib():
    a, b = 1, 1
    while 1:
        yield a
        a, b = b, a + b

# Use the fibonacci function to print out 10 digits in the sequence
import types
if type(fib()) == types.GeneratorType:
    print("Good, The fib function is a generator.")

    counter = 0
    for n in fib():
        print(n)
        counter += 1
        if counter == 10:
            break

```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/TechsquareJoseph/joes-personalpage/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
