#include <iostream>
using namespace std;

int main() {
    int n, fact = 1;
    cout << "Enter a number: ";
    cin >> n;
    try {
        if (n < 0)
            throw 1;   
        if (n > 12)
            throw 2;  
        for (int i = 1; i <= n; i++)
            fact *= i;
        cout << "Factorial of " << n << " = " << fact << endl;
    }
    catch (int x) {
        if (x == 1)
            cout << "Error: Negative number not allowed!" << endl;
        else if (x == 2)
            cout << "Error: Number too large to calculate factorial!" << endl;
    }
    return 0;
}
