#include <iostream>
using namespace std;

int main() {
    double income, tax = 0.0, netSalary;

  
    cout << "Enter your monthly income: ";
    cin >> income;

    // Tax calculation
    if (income < 50000) {
        tax = 0;
    }
    else if (income <= 100000) {
        tax = income * 0.10;  
    }
    else if (income <= 200000) {
        tax = income * 0.20;   
    }
    else {
        tax = income * 0.30;   
    }

    // Net salary
    netSalary = income - tax;


    cout << "\nTax Amount: " << tax << endl;
    cout << "Net Salary after Tax: " << netSalary << endl;

    return 0;
}
