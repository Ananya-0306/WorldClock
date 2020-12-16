# WorldClock
Get Any Country Date And Time Using Python which will be something like a World clock using Python.
For this, we need the datetime module and python’s timezone module i.e. pytz.
To install pytz python, type the below command in your terminal–

$pip install pytz

We can print the names of all countries whose timezone is available using this module using the following code–
import pytz
time_zones = pytz.all_timezones
print(time_zones)

In the similar way, we can print the date and time of any number of countries. To do this, we can create the list of desired countries for which we want to get current date and time and can use for loop to print all date and time of all the desired countries.

ENJOY :-)
