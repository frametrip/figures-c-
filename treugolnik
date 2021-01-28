#include <iostream>
using namespace std;
void MyFunction() {
    int space, rows;

    cout << "Enter number  rows: ";
    cin >> rows;

    for (int i = 1, k = 0; i <= rows; ++i, k = 0)
    {
        for (space = 1; space <= rows - i; ++space)
        {
            cout << "  ";
        }

        while (k != 2 * i - 1)
        {
            cout << "* ";
            ++k;
        }
        cout << endl;
    }
}

int main()
{
    MyFunction();

}
