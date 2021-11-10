# Task_20-nov-2021
#include <iostream>

using namespace std;

int main()
{
    int range, num, insideloop, secondLoop, start;
    
    cout << "Enter the first value of loop: ";
    cin >> start;
    cout << "range of the loop: ";
    cin >> range;
    cout << "Enter the number: ";
    cin>> num;
    
    if ( range>start )
    
    for ( int p=start; p<=range; p++ )
    {
       cout <<num<<" * "<<p<<" = "<<p*num<<endl;
    }
    else if(range < start)
    {
        for(int put=range ; put>=start; put++)
    
       cout << "Range is less than startup \n\t 'TRY AGAIN' \n";
      
    }
      return 10;
}
