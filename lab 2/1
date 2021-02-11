#include <iostream>

using namespace std;

int main()

{
    int a, b, c;
    cin >> a >> b >> c;
    if (b < c)
        swap(b, c);
    if (a < b)
        swap(a, b);
    if (a < b + c)
        cout << "impossible";
    else
    {
        if (a * a == b * b + c * c)
            cout << "right";
        if (a * a < b * b + c * c)
            cout << "acute";
        if (a * a > b * b + c * c)
            cout << "obtuse";
    }
    return 0;
}


