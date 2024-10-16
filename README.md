#include <iostream>

using namespace std;

int main() {
    int result = 0, cont = 0, n1, n2;

    cout << "Number: ";
    cin >> n1;
    cout << "Number: ";
    cin >> n2;

    while (cont < n2) {
        result += n1; //resul
        cont++;
    }

    cout << n1 << " x " << n2 << " = " << result << endl;

    cout << "\nThat's the same of: ";

        for (int i = 1; i <= n1; i++) {

            if (i < n1) {
                cout << n2 << " + ";
            }

            else {
                cout << n2 << " = ";
            }
        }
        cout << result << endl;



    return 0;
}
