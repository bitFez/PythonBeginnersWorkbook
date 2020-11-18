# Looping - While Loops
Computers can be programmed to continue repeating code ***while*** a condition has not been met.

<table>
<tbody>
<tr>
<td>
<img alt="Tube Map" style="border-width:0" src="../images/tube_stops.jpg" height="200px" /> 
<!-- https://62andthenext10pathways.blogspot.com/2015/02/bakerloo-line-regents-park.html -->
<!-- ![Tube Map](../images/tube_stops.jpg) -->
</td>

<td> 

```python
stop = int(input("What stop are we at?"))
while age != "Waterloo":
    print("This isn't our stop.")
    stop = int(input("What stop are we at?"))
```

</td>
<td>

As you can see in the example on the left, the code will keeping iterating and asking the same question ***while*** the answer is not *Waterloo*.

Notice the nesting of statements underneath the while? It is the *indented* code that will keep looping.

</td>
</tr>
</tbody>
</table>

Task 1
Write a *while loop* to ask someone what the best football team in the world is. Repeat the question until they say the correct team. Test it in Python and write your answer and explanation in the table below. Share the code with your teacher and class. 

```







```

Task 2
Try to write your own infinite while loop like the one above. This is a hard task but you can be creative and make code for whatever you want. Test it in Python and write your answer and explanation in the table below. 

```







```

Task 3
Now we will try to write one more while loop this time using a condition. Again this task is a lot harder. Look at the example below and try to write your own.
<table>
<tbody>
<tr>
<td> 

```python
secret_number = 6
guesses = 3
while guesses > 0:
    print("Can you guess what number I am thinking?")
    guess = int(input("write a number "))
    if guess == secret_number:
        print("Well done, you guessed correctly!")
        break
    else:
        guesses = guesses -1
             
if guesses == 0:
    print("You have no guesses left!")
```

</td>
<td>

This is a little more complicated. it may be a good idea to write this out as a flowchart to help you think about how the code works.

In this code, we also learn of the `break ` statement. This will tell the PC to skip to the next line of code that is not in the current indented nesting. 
(Alternatively we could replace break with `guesses = 0`)

</td>
</tr>
</tbody>
</table>

Task 4 (A little harder :puzzled: )
The code below shows an example of how to add a list of numbers together:
```python
count = 5
number = 0
print("this programme will work out the total of a list of numbers")
while count > 0:
    number = number + int(input(print("Please enter a number :")))
    count = count - 1
print(number)
```

Edit this code in the box below to also divide the total by `5` and also print this.
```  











```