# Testing Tips and Tricks
Tips and Tricks for Testing Software.

## Time, Dates and Calendars

Time is difficult. Here are some useful common edge cases:

### Leap Years
* 2024 is a leap year
* February 2024 has 29 days, not 28

### Leap Seconds
Not so frequent as leap years, see https://en.wikipedia.org/wiki/Leap_second

### Natural and Artifical Time  
In time zone id `Europe/Copenhagen` in 2024, the switch from natural to artificial ("summer") time was on Sunday the 31st of March.
Thus March month began on `2024-02-29T23:00:00+00:00` (in local offset `2024-03-01T00:00:00+01:00`)  and ended on `2024-03-31T22:00:00+00:00` (`2024-04-01T00:00:00+02:00`). 
Note the change to artificial summer time on the 31st of March. 
