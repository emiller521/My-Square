****Creating a program which displays a beautiful square**** .

my_square(5,3) should display:

	$>./a.out 5 3
	o---o
	|   |
	o---o
	$>

my_square(5, 1) should display:

	$>./a.out 5 1
	o---o
	$>

my_square(1, 1) should display:

	$>./a.out 1 1
	o
	$>

my_square(1, 5) should display:

	$>./a.out 1 5
	o
	|
	|
	|
	o
	$>

my_square(4, 4) should display:

	$>./a.out 4 4
	o--o
	|  |
	|  |
	o--o
	$>

****TESTING CODE:****

	0.
	$>gcc my_file.c
	$>./a.out
	
	1.
	int main(int ac, char **av);
	
	2.
	int x = atoi(av[1]);
	int y = atoi(av[2]);
	
	3.
	Be careful segfault. :-)


