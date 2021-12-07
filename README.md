# s2_PaulVincentRobedillo

#include <iostream>
#include <string>
#include <math.h>
using namespace std;

int main() {
    string userInput;
    cout << "Enter your Full name:" << endl;
    cin >> userInput;

    int n;
    long double factorial = 1.0;

    cout << "Enter a positive integer: ";
    cin >> n;

    if (n < 0)
        cout << "Error! Factorial of a negative number doesn't exist.";
    else {
        for (int i = 1; i <= n; ++i) {
            factorial *= i;
        }
        cout << "Factorial of " << n << " = " << factorial;

        int n;

        cout << "Enter the positve Intiger:" << endl;
        cin >> n;

        for (int i = 50; i >= 40; i--) {
            cout << n << "*" << i << "=" << n * i << endl;

        }

        int j = 5;
        cout << "Exponent power" << endl;
        while (j <= 0) //Exponent
        {
            cout << Input << "*" << j << " = " << pow(Input, j) << endl;
            j++
        }



        return 0;
    }
}
