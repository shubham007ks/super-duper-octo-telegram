//This is a c++ program to crearte the table of a given number and upto any digit.


#include<iostream>

 using namespace std;
 
 int main()
 {
  int a,b,i,n;
  cout<<"Enter a number to print the table of that number :";
  cin>>a;
  cout<<endl;
  cout<<"upto how many digits you want nto print the table:";
  cin>>n;
  for(i=1;i<=n;i++)
    {
        b=a*i;
		cout<<a<<"*"<<i<<"="<<bBB"\n";
	}	
 return 0;
}
