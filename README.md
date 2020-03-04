Week 6 in-class exercise and homework.

In-class exercise:
	1. Implement print cities function in main.c
	2. Let the compute avg function can use population as metric.
	3. Any TODO in the file

Homework:
	You need to create a new library that provide function that can search city by name. The function name should be take the user input string, match it with the cities' in the "cities" array. If there is a match, print out the population of that city, if not, print out all the city name that start with the input string.
	Example:
		input: Delhi; the program print out: 16787941
		input: Mexico; the program print out: Mexico city,
		input: Be; the program print out: Beijing, Bengaluru,
		input: B; the program print out: Bangkok, Beijing, Bengaluru,

	You should have your library included in the city.h so that the main function can access the function you created. The loop in the main function will be called repeatly.

	You should modify the Makefile that can compile with your library and execute with "make search" command.
