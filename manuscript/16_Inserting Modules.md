# Inserting Modules
While Python includes a lot of functions like print, it leaves out a lot of functions that we can load into our code if we need it. Think of a module as a book with instructions on how to do something. These modules are stored by Python in a library until we need our code to know how to use them. By not loading them all at the beginning, our code takes up less memory on our computer.
The code below shows an example of how to add timing to our code.

<table>
<tbody>
<tr>
<td> 

```python
import time             # This line loads the module for time

count = 10
while count >0:
    print(count)
    count = count - 1
    time.sleep(1)       # Sleep is a function in the time module which pauses 
                        # your code for a stated amount of seconds. 1 in this case.
print("Time is up!")
```

</td>

</tr>
</tbody>
</table>

Task 1
Create a code to count from 0 to 10. Write the answer below and share with your teacher.
You will need the sleep function.

```







```

Task 3
When importing modules into your code, Python loads many functions into the memory. This could slow down how fast it takes to execute your code when it’s time to run it.
Within the time module, there are many functions that we didn’t use such as `clock`. We can choose to load just the function we need from a module like this:

```python 
from time import sleep
```

In order to use the function such as sleep, it now needs to be written into the code differently.
<table>
<tbody>
<tr>
<td>How it was written before (x is represents seconds)</td>
<td>How it should be written now</td>
</row>
<row>
<td> 

```python
time.sleep(x)
```

</td>
<td>

```python
sleep(x)
```

</td>
</tr>
</tbody>
</table>
Re-write your code to reflect the changes.