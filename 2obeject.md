#include <iostream>
using namespace std;

class Student
{
	private:
		int rno;
		char sname[30];
		char course[20];
		float percentage;
	public:
		void accept()
		{
			cout<<"Enter student details \n";
			cin>>rno>>sname>>course>>percentage;
		}
		void display()
		{
			cout<<rno<<" "<<sname<<" "<<course<<" "<<percentage<<" "<<endl;
		}
};
int main()
{
	Student x,y;
	x.accept();
	y.accept();
	cout<<"Display student data: \n";
	x.display();
	y.display();
	return 0;
	
}
