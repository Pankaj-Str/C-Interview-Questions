// C program to check whether
// a number is palindrome or not
#include <stdio.h>

// Driver code
int main()
{
	// Define variables

	// This is our given number
	int original_number = 12321;

	// This variable stored reversed digit
	int reversed = 0;

	int num = original_number;

	// Execute a while loop to reverse
	// digits of given number
	while (num != 0)
	{
		int r = num % 10;
		reversed = reversed * 10 + r;
		num /= 10;
	}

	// Compare original_number with
	// reversed number
	if (original_number == reversed)
	{
		printf(" Given number %d is a palindrome number",
				original_number);
	}
	else
	{
		printf(" Given number %d is not a palindrome number",
				original_number);
	}
	return 0;
}
