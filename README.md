# c-1
Pattern hollow square
include<stdio.h>
int main()
{
for(int i=1;i<=5;i++){
for(int j=1;j<=5;j++){
printf("%dX%d=%d\t",j,i,i*j);
}
printf("\n");
}
return 0;
}
