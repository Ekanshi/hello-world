#include<iostream.h>
#include<conio.h>
int main()
{
  char str1[10] = "Hello";
  char str2[10] = "hello";
  int i = 0;
  
  do
  {
    if(str1[i] == str2[i])  
    i++;
    else
    {
      cout<<"not equal";
      exit(2);
    }
  }while();  

}
