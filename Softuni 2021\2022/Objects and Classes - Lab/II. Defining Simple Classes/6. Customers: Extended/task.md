Use the class from the previous problem. If you receive a customer, which already exists (first name and last name
should be unique) overwrite the information.

Hints:
Check if the given customer already exists with the first and the last name. We can use LINQ as well: FirstOrDefault
returns the first occurrence or the default value (null in this case).
If the given customer exists, remove it from the current list.
Add new customer with the correct information.
Finally, print the needed information.
