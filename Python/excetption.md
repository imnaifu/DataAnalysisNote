~~~ python

# suppose we want our float function to return the input value, we can do this using the folowing code.
def return_float(x):
    try:
        return float(x)
    except:
        return x

print return_float('4.55')
print return_float('big data') # This time it didnt return a value error

4.55
big data

#print float((9,8))  ->this will return a type error, remove the comment and check the output.
def return_float(x):
    try:
        return float(x)
    except(TypeError, ValueError):# type error and value error are mentioned as a exception values
        return x
print return_float((9,8))  #now you can see it returns 9,8

(9, 8)


~~~ 
