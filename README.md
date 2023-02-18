
#include <stdio.h>

int main()
{
    int x,y,i,es,os;
    printf("Enter the two numbers : ");
    scanf("%d %d",&x,&y);
    for(i=y;i<=x;i=i+y) {
        printf("%d ",i);
        if(i%2==0) {
            es=es+i;
        }
        else {
            os=os+i;
        }
    }
    printf("\n");
    printf("%d %d",es,os);
}
