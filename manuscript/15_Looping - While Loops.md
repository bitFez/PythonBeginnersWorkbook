# Looping - While Loops
Computers can be programmed to continue repeating code ***while*** a condition has not been met.

<table>
<tbody>
<tr>
<td> 

```python
temp = int(input("What's the temperature in celcius?"))

if temp < 8:
    print("Brr, its a cold day!!!")
elif temp >= 8 and temp < 15:
    print("I'ts a mild day")
elif temp >= 15  and temp < 21:
    print("Its a warm day")
elif temp >= 21:
    print("It's a hot day")
else:
    print("sorry, you must enter a number")
```

</td>
<td>

As you can see in the example on the left, the code will keeping iterating and asking the same question ***while*** the answer is not *Batman*.

Notice the nesting of statements underneath the while? It is the indented code that will keep looping.

</td>
</tr>
</tbody>
</table>
