# Date and time  

import datetime  #here datetime is module this is how we import date time and year 

date.object = datetime.date(2007,6,12)  #YYYY-MM-DD  #if we use datetime.today() it will show todays date
print(day)


print(date.object.year)  #only print the year 
print(date.object.month) #only print the date 
print(date.object.day) #only print the day


#now lets go to time__________________________________________________________________________

time_object = datetime.time(21,4,34)
print(time_object)

print(time_object.hour) #only print the hour
print(time_object.minute)  #only print the minute
print(time_object.second)  #only print the second


#we can also write by combaining the date and time lets see how to combain those together

form datetime import datretime

date_time_obj = datetime(2007, 6, 12, 21, 10, 43)  #years month date hours minute and seconds   #if we want current date and time we can use {now}

date_time_obj = datetime.now()

print(date.object.year)  #only print the year 
print(date.object.month) #only print the date 
print(date.object.day) #only print the day
print(time_object.hour) #only print the hour
print(time_object.minute)  #only print the minute
print(time_object.second)  #only print the second
