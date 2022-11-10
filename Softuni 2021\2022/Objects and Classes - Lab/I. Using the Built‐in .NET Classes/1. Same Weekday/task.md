You are given 2 lines of input strings for 2 dates in format day‐month‐year. Compare them and check if the dates
are in the same weekday. If they are print: "Yes" and on a new line print the name of the day. If the dates are in
different days print "No".

Hints:
 Read the dates as strings from the Console.
 Split the input by "‐" and you will get the day, month and year as numbers. Now you can create new
DateTime(year, month, day).
 The newly created DateTime objects have a DayOfWeek property so you can compare them.
