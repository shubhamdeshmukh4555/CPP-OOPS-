#include <iostream>
using namespace std;
 
void show(int a , int b = 7, int c = 11)
{
	cout<<a<<" "<<b<<" "<<c<<endl;
}

int main()
{
	cout<<" Default argument function :\n";
 //Here 9 value will give to a varibale 
	show(9);
 //Here 9 value give to a and 4 value give to b 
	show(9,4);
 //Here 9 value give to a and 4 value give to b & and 17 to c
	show(9,4,17);
	return 0;
}
