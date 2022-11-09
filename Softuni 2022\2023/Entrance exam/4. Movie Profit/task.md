Write a program that tracks movie profits. Until you receive the command "End", you will be given movie names
and screening profits. Your task is to calculate the accumulated profit for each movie from all its screenings. If you
receive the command "Canceled" then after it any screening of the movie to which it refers will not take place
and the profit should not be added to the already accumulated profit for this movie.
Input:
 Until you receive "End ", the data will be coming in the folowing formats:
"{movie name}:{screening profit}"
or
"Canceled:{movie name}"
 The name of the movie will always be delimited by ":" from the profit
 The the canceled command will always be delimited by ":" from the name of the movie
Output:
 Print the information about each movie in the following format:
"{movie name} ‐> {total profit}"
 Sort the movie by total profit in descending order.
