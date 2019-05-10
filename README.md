
## In class exercise

1. If you wanted to reuse this program for a file that had 17 headers lines. What
line of code would you change in our program?

        Write the line of code that you will replace here:
        if LineNumber > 0: # skip first Line and blanks

        What will be the new code?

        Write the new code here:___
        if LineNumber > 16: # skip first seventeen lines and blanks

2. would happen if we don’t included `import sys` in our program?

        Write you answer here:___
        You would not import the sys module. That means that you wouldn't have
        access qto the sys.argv variable.

3. Let’s suppose that the third file that the user provides as input
has only one column. What error message will be generated?

        Write you answer here:___
        Line %d not XY format in file %s\n
                              
4. Our program split lines of input files (except the first file) into elements 
that are tab delimitated. However, data could be split by , or many other characters. 
In this case is a good idea to define a new variable that takes the delimiter provide 
by the user. Using what you learn about sys.argv in this class`. Write a variable that 
reads a delimiter (e.g ‘,’) provided as the first input file.

Write your code here:__
delimiter = sys.arv[0]
