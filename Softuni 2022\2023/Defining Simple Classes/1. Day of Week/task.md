You are given a date in format day‐month‐year. Calculate and print the day of week in English.

Hints:
 Read the date as string from the Console.
 Use the method DateTime.ParseExact(string date, format, provider) to convert the input
string to object of type DateTime. Use format “d‐M‐yyyy” and CultureInfo.InvariantCulture.
o Alternatively split the input by “‐“ and you will get the day, month and year as numbers. Now you
can create new DateTime(year, month, day).
 The newly created DateTime object has property DayOfWeek.
