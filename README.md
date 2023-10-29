#include <iostream>
#include <iomanip>
using the namespace std;
int main()
{
int num1, num2;
char opr;
cout << "Enter two integers: ";
cin >> num1 >> num2;
cout << endl;
cout << "Enter the operator: + (addition), - (subtraction), " <<" * (multiplication), / (division): ";
cin >> opr;
cout << endl;
cout << num1 << " " << opr << " " << num2 << " = ";
switch (opr){
case '+':
cout << num1 + num2 << endl;
break;
case'-':
cout << num1 - num2 << endl;
break;
case'*':
cout << num1 * num2 << endl;
break;
case'/':
if (num2 != 0)
cout << num1 / num2 << endl ;
else
cout << "ERROR \cannot be divided by zero" << endl;
break;
by default:
cout << "Illegal operation" << endl;
}
returns 0;
}
