Define a class Movie, which holds the following information about movies: Genre, Name and Duration. Write a
program, which reads N movies and prints all movies, which match certain genre.

Input:
 On the first line you will receive the number of movies – N.
 On the next N‐lines you will be receiving data in the following format: "{genre}|{name}|{duration}".
 On the last line you will receive Genre / "all". Print only the names of the movies, which are from that
Genre / All movies.

Output:
 Print only the names of the movies from the given criteria – Genre / All movies, each on a new line.

Solution:
Define a class Movie with properties: Genre, Name and Duration.
Read the input lines, make a collection and store the data.
Finally read your last line – Genre List and print the result.
You can use LINQ to filter the collection.
