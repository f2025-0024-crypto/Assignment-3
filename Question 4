#include <iostream>
using namespace std;

int main() {
    int choice;
    double distance, fare;

    cout << "Railway Seat Types:\n";
    cout << "1. Economy (Rs. 5 per km)\n";
    cout << "2. Business (Rs. 8 per km)\n";
    cout << "3. First Class (Rs. 12 per km)\n";

    cout << "\nEnter seat type (1-3): ";
    cin >> choice;

    cout << "Enter distance in km: ";
    cin >> distance;

    switch (choice) {
        case 1:
            fare = distance * 5;
            cout << "Seat Type: Economy\n";
            break;

        case 2:
            fare = distance * 8;
            cout << "Seat Type: Business\n";
            break;

        case 3:
            fare = distance * 12;
            cout << "Seat Type: First Class\n";
            break;

        default:
            cout << "Invalid seat type!\n";
            return 0;
    }

    cout << "Total Fare: Rs. " << fare << endl;

    return 0;
}
