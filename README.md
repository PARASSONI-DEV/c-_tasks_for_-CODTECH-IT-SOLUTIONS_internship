#include <iostream>
using namespace std;

int main() {
    float choice;
    float celsius;
    float fahrenheit;

    char input1;
    double input2;



    cout << "Enter c (or C) to convert Fahrenheit to Celsius or f (or F) to convert Celsius to Fahrenheit: \n";
    cin >> input1;


    if (input1 == 'c')
    {
      cout << "Enter your temperature in Fahrenheit: ";
      cin >> input2;
      cout << endl;
      cout << "Your temperature in Celsius is: " << (input2 - 32) * (5.0/9.0) << endl;
    }

    else if (input1 == 'C')
    {
      cout << "Enter your temperature in Fahrenheit: ";
      cin >> input2;
      cout << endl;
      cout << "Your temperature in Celsius is: " << (input2 - 32) * (5.0/9.0) << endl;
    }

    if (input1 == 'f')
  {
    cout << "Enter your temperature in Celsius: ";
    cin >> celsius;
    fahrenheit = (celsius * 9.0) / 5.0 + 32;
    cout << "Your temperature in Fahrenheit is: " << fahrenheit << endl;
    //cin >> input2;
    //cout << endl;
    //cout << "Your temperature in Fahrenheit is: " << (input2 * 9.0/5.0) + (32) << endl;
  }

  else if (input1 == 'F')
  {
    cout << "Enter your temperature in Celsius: ";
    cin >> input2;
    cout << endl;
    cout << "Your temperature in Fahrenheit is: " << (input2 * 1.8) + (32) << endl;
  }

    return 0;
}
3 data structures implement in c++}
