#include<iostream>
using namespace std;
class Addition
{
	private:
		int a,b;
	public:
		void accept()
		{
			cout<<"enter 2 nos \n";
			cin>>a>>b;
		}
		void add()
		{
			int c;
			c = a+b;
			cout<<"Addition of 2 nos = "<<c<<endl;
		}
};


int main()
{
	Addition x;
	x.accept();
	x.add();
	
	return 0;
	
}
