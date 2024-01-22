#include <iostream> 
using namespace std;

class Project
{
	private:
		
		int pid;
		char pname[30];
		char status[15];
	public:
		
		void accept()
		{	
			cout<<"Enter project details \n";
			cin>>pid>>pname>>status;
			
		}
		void display()
		{
			cout<<pid<<" "<<pname<<" "<<status<<endl;
		}
};

int main()
{
	int n;
	int i;
	Project x[10];
	cout<<"Enter n number of project"<<endl;
	cin>>n;
	for(i=0;i<n;i++)
	{
		x[i].accept();
	}
	cout<<"display project details"<<endl;
	
	for(i=0;i<n;i++)
	{
		x[i].display();
 	}
	
	return 0;
	
}
