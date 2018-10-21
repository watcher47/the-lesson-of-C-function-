# the-lesson-of-C-function-
this project is  write to give the example of how to define a function in C++ and how to use it.
//my first function example project1.cpp defining my own function.
#include<iostream>
#include<stdlib.h>
void simon(int);  //function prototype for simon
using namespace std;
int main()
{
	simon(3); //call the simon() function
	cout << "pick an interger；" << endl;
	int count;
	cin >> count;
	simon(count);
	cout << "program is Done!" << endl;
	system("pause");
	return 0;

}
void simon(int n) // define the simon function
{
	using namespace std;
	cout << "simon says touch your toes" << n << "times." << endl;
	//void function don't need return statements
}
// we can sum up the defintion of a function should be write like this.
//  type functionname (agumentlist)
//   { statement}
