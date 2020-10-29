# John Motson style lines of commentary
OK, this has nothing to do with football[^1]! When writing code, you should add comments to your work so that you can remind yourself later what a section of code is meant to do. Sometimes looking at lots of code can be complicated so it may be useful to add descriptive comments to help yourself and others who may be reading your code to make sense of it.

A comment is a line of text that the computer will not read as code. The computer will ignore the line and move to the next line of code.

There are 2 ways to add comments:
For a single line of commenting you simply add a hash (#) in front of the line that is a comment.
For comments that will be written over several lines, you can add 3 quotation marks before and after your comments. This can be either single or double quotation marks (`'''` or `"""`)

Type the following code into Python and see what happens when you try to run it:

```
# This line of text is ignored. The next line prints some text
print("My name is...")

# This line is ignored
print("My name is...")

# This line is ignored
print("My name is...")

'''
When you need to have
several lines of commentary
like this, you can use 3 
quotation marks.
'''
print("Slim Shady")
```



Although there will not be many lines of commentary in this book, you should make a habit of adding them to each line of your code like the one above to explain what each code does. 

[^1]: At the time I had written the first version of this book, John Motson was a famous commentator. At the time of re-writing this edition of the workbook, Motson has now retired and younger coders may not recognise the name!
