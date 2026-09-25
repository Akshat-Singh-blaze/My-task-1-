#include <iostream>
using namespace std;

int main( )
{
  double num1, num2;
    
  cout << "Enter first number: ";
  cin >> num1;
    
  cout << "Enter second number: ";
  cin >> num2;
    
  cout << "\nAddition: " << num1 + num2 << endl;
  cout << "Substraction: " << num1 - num2 << endl;
  cout << "Multiplication: " << num1 * num2 << endl;
    
  if (num2 == 0)
  {
    cout << "Divison: Cannot divide by zero." << endl;
  }
  else 
  {
    cout << "Division: " << num1 / num2 << endl;   
  }
  return 0;
}
