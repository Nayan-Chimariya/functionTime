# functionTime
Decorator to time your function

## How to use

### Import the clockIt function
```python
from functionTime import clockIT
```
This will import the clockIT function from the package which is a decorator function
that you can use to decorate your function with. Calling the function will show its runtime.

### Example

```python
from functionTime import clockIT

@clockIT
def hello():
  print("test")

hello()
```
Caliing the hello() function will do its intended function and its runtime will also be printed.





