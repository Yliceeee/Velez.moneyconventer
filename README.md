#include <iostream>
 
using namespace std;

int main() {
	{
		float peso = 1.00;
		float dollar = 0.018;
		float amount = peso * dollar;
		
		cout << "Money Conventer\n";
		cout << "Input money in peso\t:";
		cin >> peso;
		
		amount = peso * dollar;
		
		cout << "The amount in dollar is\t" << amount << endl;
		
	}
	
	{
		float dollar = 1.00;
		float peso = 56.00;
		float amount = dollar * peso;
		
		cout << "Money Conventer\n";
		cout << "Input money in dollar\t:";
		cin >> dollar;
		
		amount = dollar * peso;
		
		cout << "The amount in peso is\t" << amount << endl;
		
		return 0;
		
		}
	}	
