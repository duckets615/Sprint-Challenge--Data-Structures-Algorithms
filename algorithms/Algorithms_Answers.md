Example 1

A) O(n), as the number increases, the number of iterations also increases at a steady rate. In this case for example, if n is 3, it'll loop 3 times, but if n is 10, it'll loop 10 times.
B) O(n^c), nested loops that all get their length based off n means each one will grow as n grows
C) O(n), as n increases, so will the number of calls, but nothing in the code will modify the number of times it's called

Example 2

Starting at the middle floor (start = n/2), drop an egg, and if it fails to break, go to the middle floor between the starting floor and the top of the building (n /start) and repeat until it breaks .If the egg did break when dropped from there, go down to the middle floor between the current floor current and the bottom floor and repeat until it doesn't. you now have the running time.
