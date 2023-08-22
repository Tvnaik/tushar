#include<iostream>

using namespace std;

int rn(int n)
{
    int r=0;
    
    while(n>0){
     int last=n%10;
    r=r*10+last;
    n=n/10;
    }
    
    return r;
}
int main()
{
int a;
cout<<"enter the number ";
cin>>a;

int reverse=rn(a);
cout<<"reverse number is "<<reverse;

return 0;
}
