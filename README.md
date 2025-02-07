#include <iostream>
#include<cmath>
using namespace std;

int main() {
        int a, res=0,num;
    cin >> a;
    num = a;
    while (a > 0)
    {
        int digit = a % 10;
        res = res * 10 + digit;
        a /= 10;
    }
   
   if (res % num == 0)
        cout << res << "\nYES";
    else
        cout << res << "\nNO";


}
