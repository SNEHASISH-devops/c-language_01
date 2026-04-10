#include<stdio.h>
int main(){
    int a,b,c,ch;
    printf("***CHOICE ANY ONE***\n");
    printf("1.SWAP OF TWO NUMBERS\n");
    printf("2.SWAP OF TWO NUMBERS WITHOUT USING THIRD VARIABLE\n");
    printf("3.EVEN OR ODD\n");
    printf("ENTER THE CHOICE:");
    scanf("%d",&ch);
    switch(ch){
        case 1:
            printf("ENTER THE TWO NUMBERS:");
            scanf("%d%d",&a,&b);
            printf("BEFORE SWAP:a=%d b=%d\n",a,b);
            c=a;
            a=b;
            b=c;
            printf("AFTER SWAP:a=%d b=%d\n",a,b);
            break;
        case 2:
            printf("ENTER THE TWO NUMBERS:");
            scanf("%d%d",&a,&b);
            printf("BEFORE SWAP:a=%d b=%d\n",a,b);
            a=a+b;
            b=a-b;
            a=a-b;
            printf("AFTER SWAP:a=%d b=%d\n",a,b);
            break;
        case 3:
            printf("ENTER THE NUMBER:");
            scanf("%d",&a);
            if(a%2==0){
                printf("IS EVEN NUMBER\n");
            }
            else{
                printf("IS ODD NUMBER\n");
            }
            }  
return 0;  
    }# c-language_01
