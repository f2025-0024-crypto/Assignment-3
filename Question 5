#include <iostream>
using namespace std;

int main() {
    string username, password;
    const string correctUser = "admin";
    const string correctPass = "12345";

    int attempts = 0;

    while (attempts < 3) {
        cout << "Enter username: ";
        cin >> username;

        cout << "Enter password: ";
        cin >> password;

        if (username == correctUser && password == correctPass) {
            cout << "Login Successful!" << endl;
            return 0;   
        } else {
            cout << "Invalid username or password. Try again." << endl;
            attempts++;
        }
    }

    // If loop ends after 3 failures
    cout << "Account Locked!" << endl;

    return 0;
}
