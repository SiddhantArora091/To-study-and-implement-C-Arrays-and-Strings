#include <iostream>
using namespace std;
int main() {
    int arr[50], num, temp, i, j;
    cout << "Enter total count: ";
    cin >> num;
    for(i = 0; i < num; i++) {
        cout << "Element " << i + 1 << ": ";
        cin >> arr[i];
    }
    cout << "Original array: ";
    for(i = 0; i < num; i++) cout << arr[i] << " ";
    cout << endl;
    for(i = 0, j = num - 1; i < num / 2; i++, j--) {
        temp = arr[i];
        arr[i] = arr[j];
        arr[j] = temp;
    }
    cout << "Reversed array: ";
    for(i = 0; i < num; i++) cout << arr[i] << " ";
    cout << endl;
    return 0;
}
/*Output:-
Enter total count: 2
Element 1: 1234
Element 2: 56789
Original array: 1234 56789 
Reversed array: 56789 1234 
*/
