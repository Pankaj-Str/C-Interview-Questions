// C program to find LCM
// of two numbers
#include <stdio.h>

// Recursive function to return
// gcd of a and b
int gcd(int a, int b)
{
	if (a == 0)
		return b;
	return gcd(b % a, a);
}

// Function to return LCM of
// two numbers
int lcm(int a, int b)
{
	return (a / gcd(a, b)) * b;
}

// Driver code
int main()
{
	int a = 15, b = 20;
	printf("LCM of %d and %d is %d ",
			a, b, lcm(a, b));
	return 0;
}
