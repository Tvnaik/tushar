#include <iostream>
using namespace std;

void fibo(int n)
{
    int first=0;
    int second=1;
    cout<<"fibonaci series of "<< n <<" is ";
    
    for(int i=0;i<n;i++)
    {
        cout<<first;
        int next=first+second;
        
        first=second;
        second=next;
        
    }
    cout<<endl;
}

int main(){
    int a;
    cout<<"enter the number :";
    cin>>a;
    
    fibo(a);
    return 0;
}
