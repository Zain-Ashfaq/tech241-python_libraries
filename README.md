# Libraries

Libraries are collections of functions (pre-built code) that do a job for you. We can import these libraries to make our own code easier to understand, be less complex, and faster to write.

```python
from random import randint, random
import math
```
The above code imports the randint and random functions from the random library, as well as the entire math library.

```python

print(random())
```
This code generates a random floating-point number between 0 and 1 using the random() function and prints it.

```python

num_float = 23.1
print(math.ceil(num_float))
print(math.floor(num_float))
```
Here, the code assigns the value 23.1 to the variable num_float. It then uses the math.ceil() function to round up the value of num_float to the nearest integer and prints the result. Similarly, the math.floor() function is used to round down the value of num_float to the nearest integer and print the result.

```python

print(math.pi)
```
Finally, this code prints the value of the mathematical constant pi, which is provided by the math library.