# FunctionOverloading c++
#include<iostream>
using namespace std;
int min(int a, int b)
{
	cout << "using int min ";
	if (a < b)
		return b;
	else return a;
}
double min(double a, double b)
{
	cout << "double min()";
	if (a>b)
		return b;
	else return a;
}
int main()
{
	int a = 5, b = 10;
	double x = 78, y = 79;
	int c = min(a, b);
	double z = min(x, y);
	cout << c<<endl;
	cout << z;
	system("pause");
}
