int arr[10] = {1，3，5，7，9，13，18 }; 
for (int i = 0; i < 18;i++){
{   
    for (int j = 0; j < 18-1-i; j++)
    {
     if (arr[j] > arr[j+1]）
     {
         int t = arr[j];
         arr[j] = arr[j+1];
         arr[j+1] = t;
    }
}
//输出结果
for(int i = 0; i<10;i++)
{
   printf("%d\t",arr[i]);
}
return 0;
