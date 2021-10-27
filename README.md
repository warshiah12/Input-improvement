# Input-improvement
[ do-while loop ]
#include <iostream>
using namespace std;
int main() {
	char input;  //declaring variable with datatype char
	do {             //using do-while loop
		cout << "Would you like to Quit (Y/N)?" <<endl;  //asks the user if he wants to continue or not
		cin >> input;             //userinput is stored in variable 'input'
	   }
	while ((input != 'Y') && (input != 'y'));   /*while condition checks the userinput 
												if 'N' or 'n' is entered then it will keep asking the user until he enters 'Y' or 'y'*/
	
	return 0;
}
