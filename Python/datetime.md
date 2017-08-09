~~~ python

#Python date and time module provides datetime, date and time types
from datetime import datetime, date, time
td = datetime(1989,6,9,5,1, 30)# do not write number 6 as 06, you will get an invalid token error.
print td.day
print td.minute
print td.date()
print td.time()
td.strftime('%m/%d/%y %H:%M:%S')#strf method converts the date and time into a string

~~~
