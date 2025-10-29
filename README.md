#include <stdio.h>

int main(){
    int arr[10] = {1,3,5,7,9,13,0,2,8,4};
    int n=10;
    
    for (int i = 0; i < n-1;i++){
{   
    for (int j = 0; j < n-1-i; j++)
    {
     if (arr[j] > arr[j+1]）{
         int t = arr[j];
         arr[j] = arr[j+1];
         arr[j+1] = t;
    }
}
//输出结果
    for(int i = 0; i<10;i++){
        printf("%d\t",arr[i]);
    }
    return 0;
}    
    

