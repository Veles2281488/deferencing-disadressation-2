#include <iostream>

using namespace std;

int main()
{
	int b = 300;
	int* a = &b;

	cout << "adress \t *a\t b\n";

	cout << a << "\t" << *a << "\t" << b << endl;
	b += 50;
	cout << a << "\t" << *a << "\t" << b << endl;
	*a = 150;
	cout << a << "\t" << *a << "\t" << b << endl;

	return 0;

}
