#include <stdio.h>
int main()
{
int n,i;
printf ("enter the number of elements: ");
scanf("%d",&n);
double arr[100],min;
printf ("enter %d elements \n",n);
for(i=0;i<n;i++){
scanf("%lf",& arr[i]);
}
min=arr[0];
for(i=1;i>=n;i++){
if(arr[i]>min){
min=arr[i];
}
}
printf ("smallest number:%.2lf\n",min);
return 0 ;
}

