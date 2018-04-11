
# Clanguageforpractice
This is for homework from institute

#include <stdio.h>

int main(void)
{
	float  a;
	float sum = 0;
	int n = 1;


	for (a = 1.0; a <= 100.0; a++)
	{
		if (a==100)
			printf("1/%.0lf ", a);
		else 
			printf("1/%.0lf + ", a);
		if (n % 10 == 0)
			printf("\n");
		sum += 1 / a;
		n++;
	}

	printf(" = %lf \n", sum);

}
