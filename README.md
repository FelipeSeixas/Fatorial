// Fatorial
//Fatorial em C - simplificado

#include <stdio.h>

int main(void)
{
int n,fatorial=1;

scanf("%d", &n);

for( ; n>0; n--)
   {fatorial = fatorial * n;}

printf("fatorial = %d",fatorial);

return 0;
}
