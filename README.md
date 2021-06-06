/*# size-of-the-char-float-double-and-int
A C++ program to find size of int, float, double and char in my system
*/


#include <iostream>
using namespace std;

int main() 
{    
    cout << "Size of the Char, float, double and int are given below" << endl;
    cout << "Size of char: " << sizeof(char) << " byte" << endl;
    cout << "Size of int: " << sizeof(int) << " bytes" << endl;
    cout << "Size of float: " << sizeof(float) << " bytes" << endl;
    cout << "Size of double: " << sizeof(double) << " bytes" << endl;

    return 0;
}
