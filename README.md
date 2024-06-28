# Student-s-grade-calculator-using-C
 This is an easiest way to calculate  one's grade using marks
/******************************************************************************

#include <stdio.h>

int main()
{                  // grade calculator
    int marks;
    printf(" enter your marks");
    scanf(" %d ", &marks);
    if( marks >=0 && marks <30){
       printf(" you obtained C grade \n"); 
    }else if(marks >=30 && marks <70){
        printf(" you obtained B grade \n");
    }else if(marks >=70 && marks <90){
        printf(" you obtained A grade \n");
    }else if(marks >=90 && marks <=100){
        printf(" you secured A+ grade \n");
    }else{
        printf(" please enter valid marks \n");
    }

    return 0;
}
