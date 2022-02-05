
#include <stdio.h>
#include<math.h>
#include<time.h>
#include <stdlib.h>


int main ()
{
	int n,tahmin,i;
	int tamam=0;
	srand(time(0));
	n=rand() %100+1;

		printf("\n%d",n);
	for (i=1;i<7;i++)
	{
			printf(" %d. tahmin Sayi degeri giriniz\n", i);
			scanf("%d", &tahmin);

			if (n==tahmin)
			{
					printf("Bildiniz!\n"); tamam=1;
					break;
			}

			else if (n>tahmin) {
			printf("Kucuk girdiniz\n");
		}

			else  {
			printf("Buyuk girdiniz\n");
		}

	}
	 if(tamam==0)
		printf("\n Bilemediniz sayimiz %d idi !", n);
	}
  
