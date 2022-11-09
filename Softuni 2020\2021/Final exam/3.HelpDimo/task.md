Dimo is a professional track and field athlete. To monitor his progress and whether he has achieved the necessary results, he
needs a program. Write the program to help Dimo. First the length of the jump is read,
which Dimo must fulfill - she is his goal. Initially, he tries to perform a long jump
30 cm less than the target. Dimo can only make three jump attempts for each current target length,
with his attempt succeeding in case the length of the attempt's jump is greater than the length of
the current goal. When the athlete succeeds in jumping the current target length, it is increased by 5
centimeters. If Dimo fails to jump over the current target length 3 times, he has no more attempts and his training is considered a failure. If the target length is reached and Dimo ​​jumps over it
length, the training is successful.
Input:
Whole numbers [100...300] are sequentially fed to the input:
• On the first line – the target length in centimeters
• Until the end of the program, the lengths of the following lines are read one by one
which Dimo managed to jump every time
Output:
Print one line to the console:
• If Dimo does not jump over the target length:
o "{current target length}cm was too hard for Dimo ​​to reach. He made
{total number of attempts} tries."
• If Dimo jumps over the target length:
o "Dimo did it, he reached his goal with {the height of the latter
the current target length }cm. He made {total number of tries} tries."
