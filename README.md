#include <stdio.h>


int main()
{
    int n,i ,sum=0;
    float avg=0 ;
    printf("Enter the range:\n");
    scanf("%d",&n);
    printf("Enteries are:\n");
    for(i=1;i<=n;i++)
    {
        printf("%d\n",i);
    }
    for(i=1;i<=n;i++)
    {
        sum+=i;
    }
    printf("sum=%d",sum);
avg= (float)sum/n;  //type casting
printf("\naverage=%f",avg);
    return 0;
}
