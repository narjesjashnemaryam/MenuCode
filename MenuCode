#include <stdio.h>
#include <stdlib.h>
#include <string.h>

void fisaghors(){
    int a , b , c2;
    printf("Enter the a: ");
    scanf("%d",&a);

    printf("Enter the b: ");
    scanf("%d",&b);
    c2 = (a*a) +  (b*b);
    printf("c^2 it is : %d\n",c2);
}

void mosalas(){
    int b , h;
    float A;

    printf("Enter the b: ");
    scanf("%d",&b);

    printf("Enter the h: ");
    scanf("%d",&h);

    A = 0.5 * b * h;
    printf("The Area it is : %f\n", A);
}

void mostatil(){
    int lengh , width , A;

    printf("Enter the lengh: ");
    scanf("%d",&lengh);

    printf("Enter the width: ");
    scanf("%d",&width);
    A = lengh * width;
    printf("The Area it is : %d\n", A);
}

int main()
{
    while(1){
        printf("formol handase:\n");
        printf(" 1) fisaghors\n 2) masahat mosalas \n 3) masahat mostatil\n");
        printf("please enter the number of the Menu: ");
        int ans;
        scanf("%d",&ans);

        switch(ans)
        {
            case 1:
                fisaghors();
                break;
            case 2:
                mosalas();
                break;
            case 3:
                mostatil();
                break;
            default:
                printf("Invalid option. Please try again.\n");
                break;
        }

        char answer[5];
        printf("\nDo you want to try again? (yes/no): ");
        scanf("%s", answer);


        if(strcmp(answer, "no") == 0 || strcmp(answer, "No") == 0 || strcmp(answer, "n") == 0) {
            break;
        }
    }
    return 0;
}
