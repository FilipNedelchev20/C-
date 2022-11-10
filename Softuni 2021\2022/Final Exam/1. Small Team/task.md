With this team she communicates in а funny way. When team members want to tell her something,
they send her one sentence without any sense and she has to process it before she can read it. The
process is simple – until the command “read it now” is received, she has to execute different
transformations on the message (Reverse, Insert, Change).
You have to implement this in a program to optimize reading.

Constraints:
 Command “Reverse” – Reverse the whole message.
 Command “Insert&lt;-&gt;{text}&lt;-&gt;{index}” – Insert the given text at the given index.
 Command “Change&lt;-&gt;{oldLetter}&lt;-&gt;{newLetter}” – change the last occurance of the old letter
with the new letter.

Input:
 On the first line, you will receive a string with the funny message.
 On the next lines, you will be receiving commands.
 Some commands (Insert, Change) have parameters, split by &quot;&lt;-&gt;&quot;.

Output:
 After the &quot;read it now&quot; command is received, print this message: &quot;You have a text message:
{message}&quot;
