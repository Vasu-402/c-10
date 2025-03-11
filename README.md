#include <stdio.h>

int main() {
   int n, sum=0, i;
   printf("enter the number:\n");
   scanf("%d ",&n);
   for (int i=0;i<=n;i++)
   {
       printf("%d \n",i);
       sum= sum+i;
   }
   printf("sum= %d\n",sum);
    return 0;
}
