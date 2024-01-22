#include <iostream>
using namespace std;

class If
{
	private:
		int a;
	public:
		void enter()
		{
			cout<<"enter a number = \n";
			cin>>a;
		}
		void result()
		{
			if(a>10)
			{
			cout<<"Enter is greater than 10"<<endl;	
			}else
			{
			cout<<"Enter number is less than 10"<<endl;
			}
		}
	
};

int main()
{
	If x;
	x.enter();
	x.result();
	return 0;
}
