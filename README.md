#include <iostream>
using namespace std;

int main()
{
	int n, x;
	while (true)
	{
		cout << "Enter N\n";
		cin >> n;
		x = n / 2;
		for (int i = 0; i <=n/2; i++)
		{
			for (int k = 0; k < x-i; k++)
			{
				cout << " ";
			}
			for (int k = 0; k < 2*i+1; k++)
			{
				cout << "*";
			}
			cout << endl;
			
		}
		cout << endl << endl;

			
	}
	
}

