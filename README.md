# cpp-lab3-sb-bsu
readme.md
#include<iostream>
using namespace std;
int main()
{
    int k, i = 1, sum_k = 0; double number;
    do {
    cout << "Enter the amount of integers to sum = "; cin >> k;
    while (number-(int)number!=0)
        cout << "Nope" << endl;
        cout << "Try again" << endl;
        cin >> number;
        break;
        sum_k += number ; i++;
    } while (i <= k);
    cout << "The total of sum of " << k << " integers is: " << sum_k;
    return 0;
}
