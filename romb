#include <iostream>
using namespace std;
void MyFunction() {
    int i, j, N = 17;
    int center = N / 2;
    for (i = 0; i < N; i++)
    {
        for (j = 0; j < N; j++)
        {
            if (i <= center)
            {
                // Верхняя половина ромба
                if (j >= center - i && j <= center + i)
                    cout << "*";
                else
                    cout << " ";
            }
            else
            {
                // Нижняя половина ромба
                if (j >= center + i - N + 1 && j <= center - i + N - 1)
                    cout << "*";
                else
                    cout << " ";
            }
        }
        cout << endl;
    }

}

int main()
{
    MyFunction();

}
