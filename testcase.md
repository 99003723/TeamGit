#include <iostream> 
#include <math.h> 
using namespace std; 
  
// Function for conversion 
double Convert(double degree) 
{ 
    double pi = 3.14159265359; 
    return (degree * (pi / 180)); 
} 
  
int main() 
{ 
    double degree = 30; 
    double radian = Convert(degree); 
    cout << radian; 
    return 0; 
} 
