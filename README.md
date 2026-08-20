# Fibonacci-series-using-CPP-
this program prints fibonacci series upto given number of terms 

#include <iostream>
using namespace std;

int main()

{
    int term1,term2,term3,terms,i;
    cout<<"enter the number of terms:";
    cin>>terms;

    i=1;
    term1=1;
    term2=2;

    cout<<term1<<endl<<term2<<endl;

    while(i<=terms){

        term3=term1+term2;

        cout<<term3<<endl;

        term1=term2;
        term2=term3;

         i++;

    }


    return 0;
}
