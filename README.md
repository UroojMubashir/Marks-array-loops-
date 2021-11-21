#include <iostream>
using namespace std;

int main()
{

int sum =0;
int Marks[5];
cout<<"Kindly Enter your Marks for 5 Subjects:\n" <<endl;
    for (int i=0; i < 5; i++)
    { cin>>Marks[i];
    sum+=Marks[i];}
    
    cout<<"The Sum is:" <<endl;
    cout<<sum<<"The Average is:"<< sum /5 <<endl;
}

    
   
