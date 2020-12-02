#include<stdio.h>
#include<conio.h>
void main()
{
int p,q,i,j,k;
int a[100],b[100],c[200];
printf("\n Enter the size of 1st array");
scanf("%d",&p);
printf("\n Enter the size of 2nd array");
scanf("%d",&q);
printf("\n Enter elements of 1st array");
for(i=0;i<p;i++)
scanf("%d",&a[i]);
printf("\n Enter elements of 2nd array");
for(j=0;j<q;j++)
scanf("%d",&b[j]);
k=0;i=0;j=0;
while((i<p0&&(j<q))
{
if(a[i]<=b[j])
c[k]=a[i++];
else
c[k]=b[j++];
k++;
}
while(i<p)
{
c[k]=a[i++];
k++;
i++;
}
while(j<q)
{
c[k]=b[j++];
k++;
j++;
}
printf("merge array is:\n");
for(i=0;i<k;i++)
{
printf("%d",c[i]);
printf("\n");
}
getch();
}









