### like PHP `foreach`
~~~ python
dic = {'a':1, 'b':2, 'c':3}
for k,v in enumerate(dic):
    print(k)
    print(v)
~~~~

### loop multiple array at once
~~~ python
list_a = [3, 9, 17, 15, 19]
list_b = [2, 4, 8, 10, 30, 40, 50, 60, 70, 80, 90]

""" will stop at the shortest """
for a, b in zip(list_a, list_b):
    print(max(a,b))
~~~

### 'while else' loop
~~~ python
""" 
    out from while condition, will excute 'else'
    but if out from break, will not excute 'else'
"""
while something:
    if something:
        break;
else:
    others
~~~

### 'for else' loop
- like 'while else' 
- if ended normally, 'else' will excute
- if break in the middle of the loop, 'else' will not excute
