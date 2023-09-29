# C_problemsolving
Write a program in C to find the maximum and minimum elements in an linked list.




#include<stdio.h>
#include<stdlib.h>
struct node{
      int data;
      struct data*link;
      };
int main(){
    int arr[5]={9,5,3,8,2};
    int max,min,i;

    max = arr[0];
    min = arr[0];

    for(i=0; i<=5; i++){
        if(arr[i] < min){
            min = arr[i];
        }
        if(arr[i] > max){
            max = arr[i];
        }
    }

    printf("The maximum value is= %d\n", max);
    printf("The minimum value is= %d\n", min);

    return 0;
}



Output:
The maximum value is= 9
The minimum value is= 2
