On the first line, you will be given a string containing all of your events for the day. Until you receive the command
"End", you will be given some commands to change that initial string. The commands can be:
 "Add Event:{index}:{string}":
o Insert the given string at that index only if the index is valid
 "Remove Event:{start index}:{end index}":
o Remove the elements of the string from the starting index to the end index (inclusive) if both
indices are valid
 "Switch:{old string}:{new string}":
o If the old string is in the initial string, replace it with the new one (all occurrences)
After each command, print the current state of the string, even when the indices are not valid and no changes have
been made.
After the "End" command, print the following: "Your work calendar for the day is ready:
{string}"
Constraints
 An index is valid if it is between the first and the last element index (inclusive) in the sequence.
