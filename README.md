# my-first-code-in-c
#include <stdio.h>
#include <math.h>

int main() {
    char student[10][10];
    int dgree[10][3];
    
    for(int i=0; i<10; i++){
        printf("Enter student name :");
        scanf(" %s",student[i]);
        printf(" %s \n",student[i]);
        for(int j=0; j<3; j++){
            printf("Enter 3 course degree :");
            scanf(" %d",&dgree[j]);
        }  
      
}

    printf("\n student and thier greede");
    for(int i=0; i<10; i++){
        printf(" %s: \n",student[i]);
        for(int j=0; j<3; j++){
          printf(" %d \n",dgree[i][j]);
        }
        printf("\n");
    }
    return 0;
}
