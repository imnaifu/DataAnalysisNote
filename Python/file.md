### open()
### close()
### read()
### readline()
### 'with' expression
~~~ python
""" no need close """
""" will call __exit__() to auto close file """
with open("text.txt", "w") as textfile:
  textfile.write("Success!")

~~~
