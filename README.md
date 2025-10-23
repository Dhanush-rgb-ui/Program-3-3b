# Module-3 Day-2 SEB
## AIM:
To create a C program  to check whether the given number is Armstrong number or not  using do-while loop.

## Program:
```c
#include<stdio.h>
#include<math.h>
int main(){
    int n,i,sum=0;
    scanf("%d",&n);
    i=n;
    do{
        int digit=i%10;
        int mult=pow(digit,3);
        sum=sum+mult;
        i=i/10;
    }while(i>0);
      if(sum==n){
      printf("%d is armstrong number",n);
      }
      else{
          printf("%d is not a armstrong number",n);
      }
    return 0;
}
```
## Result:
<img width="631" height="112" alt="image" src="https://github.com/user-attachments/assets/28b70cc9-1ba9-4399-bf3e-3b11454cf23b" />

