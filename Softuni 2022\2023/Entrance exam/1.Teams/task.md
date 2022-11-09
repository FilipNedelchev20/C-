Write a program that splits people into teams.
Each teams should have a maximum of 4 people in it. If the team is full, you need to send the remaining people to
the next team with free positions.
Input
 On the first line, you will receive how many people are available to join a team
 On the second line, separated by a single space: " ", you will receive the current teams with the count of
the people in each
Output
When there is no more free positions in a team, or there are no more available people, you should print on the
console the final state of the teams separated by " " and one of the following messages:
 If there are no more available people and the teams have free positions, you should print:
"There are free positions in the teams!
{the teams separated by ' '}"
 If there are available people but no more free positions in the teams, you should print:
"There isn't enough free positions! {count available people} people are
available!
{the teams separated by ' '}"
 If the teams are full and there are no more available people, you should print only the teams separated by
single space " "
