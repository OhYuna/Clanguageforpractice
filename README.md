#include <stdio.h>

int main(void)
{
	float  a;
	float sum = 0;


	for (a = 1.0; a <= 100.0; a++)
	{
		if (a==100)
			printf("1/%.0lf \n", a);
		else 
			printf("1/%.0lf + ", a);
		sum += 1 / a;
	}

	printf(" = %lf \n", sum);
}
