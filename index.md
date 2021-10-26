```markdown
_    _        _                               _ 
| |  | |      | |                             | |
| |  | |  ___ | |  ___  ___   _ __ ___    ___ | |
| |/\| | / _ \| | / __|/ _ \ | '_ ` _ \  / _ \| |
\  /\  /|  __/| || (__| (_) || | | | | ||  __/|_|
 \/  \/  \___||_| \___|\___/ |_| |_| |_| \___|(_)
```
My name is Joseph, and I work for [Techsquare](http://www.techsquare.com/) at the [Massachusetts Green High Performance Computing Center](https://www.mghpcc.org/).

I got this job during the summer of 2021, and started this September.

### What I'm Doing

Currently I am working through a list of training exercises to make sure I am up to par with what will be required of me in the job, and building this website is one of those items!

### A code sample of a Fibonacci number generator that I wrote:

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

For more scripts see my [Python Scripts GitHub Repo](https://github.com/TechsquareJoseph/python-scripts.git).

Have a nice day!
