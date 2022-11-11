Part A
Create public class News with namespace Newspaper with the following properties:
 Title – a string
 Text – a string
 Writer – a string
The class should have a constructor and the following methods:
 Edit (new text) – change the old text of the news with the new one
 ChangeWriter (new writer) – change the writer
 Rename (new title) – change the title of the news
 Override the ToString method – print the news in the following format:
"{title} ‐ {text}: {writer}"
Check out your solution so far in Judge.

Part B
Rename the Program.cs to StartUp.cs make the StartUp class public and make sure that it is in the correct
namespace Newspaper.
Write a program that reads and changes news. You will receive the input in the following format "{title}, {text},
{writer}". On the next line, you will receive a number n, representing the number of commands, which will follow
after it. On the next n lines, you will be receiving the following commands:
 "Edit: {new text}"
 "ChangeWriter: {new writer}"
 "Rename: {new title}"
At the end, print the final state of the newspaper.
Check out your solution in Judge.
