# linear-congruential-generator

 basic linear congruential generator to calculate pseudo-random numbers. It does the following:

Prompts the user to enter values for:
X0: The seed value
a: The multiplier
C: The increment
m: The modulus
Checks if m is a prime number using the isprime() function.

Checks if C is 0 using the EqualZero() function.

Calculates the period of the generator based on whether m is prime and C is 0. The period indicates when the sequence of numbers will start repeating.

Calculates a new pseudo-random number Xi on each iteration of the while loop using the formula:

Xi = (a*Xi-1 + C) mod m

Prints the pseudo-random number and increments the iteration counter.

Continues looping until the period is reached, then prints a message.

This allows the user to configure the parameters of a basic linear congruential generator and see the resulting pseudo-random number sequence.
