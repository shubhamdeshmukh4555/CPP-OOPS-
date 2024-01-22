#include <iostream>
#define PI 3.14
using namespace std;

class Circle
{
	private:
		float r;
	public:
		void accept()
		{
			cout<<"Enter radious of circle = \n";
			cin>>r;
		}	
		void area()
		{
			float a;
			a = PI*r*r;
			cout<<"Area of circle = "<<a<<endl;
		}
		void perimater()
		{
			float p;
			p=2*PI*r;
			cout<<"Perimater of circle = "<<p<<endl;
		}
};

int  main()
{
	Circle x;
	x.accept();
	x.area();
	x.perimater();
	return 0;
}
