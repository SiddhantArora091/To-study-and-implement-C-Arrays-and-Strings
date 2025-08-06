#include <iostream>
using namespace std;
int main(){
    int arr[6], sum=0, max, min;
   cout<<"Enter 6 numbers:\n";
    for(int i=0;i<6;i++){
        cin>>arr[i];
        sum+=arr[i];
        if(i==0) max=min=arr[i];
        else{
            if(arr[i]>max) max=arr[i];
            if(arr[i]<min) min=arr[i];
     }
        
    }
   double average=(double)sum/6;
  cout<<"\nArray elements: ";
    for(int i=0;i<6;i++) cout<<arr[i]<<" ";
    cout<<"\nSum: "<<sum;
    cout<<"\nAverage: "<<average;
    cout<<"\nMax: "<<max;
    cout<<"\nMin: "<<min;
return 0;
}
/*Output:-
Enter 6 numbers:
1
2
3
4
5
6

Array elements: 1 2 3 4 5 6 
Sum: 21
Average: 3.5
Max: 6
Min: 1
*/
