#include <stdio.h>
#include<math.h>
int main()
{
  float X,P,disc,sum;
  scanf("%f %f",&X,&P);
  sum=X;
 // float newwp = X;
// printf("%f %f",P,X);
for(int i=0;X!=0;i++)
{
  disc=trunc(X*P)/100;
  //printf("%f",disc);
  X=trunc(X-disc);
sum+=X;

}
printf("%f\n",sum);
    return 0;
}
