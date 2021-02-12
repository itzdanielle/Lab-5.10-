# Lab-5.10-
#include <iostream>
using namespace std;

int main() {
  double hour;
  double min;
  double second;  
  double midnight;
  
  cout << "Enter the hour of the day:\n";
  cin >> hour;
  
  cout << "Enter the minutes of the hour:\n";
  cin >> min;
  
  cout << "Enter the seconds passed in the current minute\n";
  cin >> second;

  midnight = 3600 * hour + 60 * min + second;
  cout << "The time in seconds since midnight is: " << midnight << endl; 
  
  
  
}
