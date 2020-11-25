#include<iostream>
using namespace std ;
int main() 
{
  cout<<" size of int = " <<sizeof(int)<<endl ;
  cout<<" size of char = " <<sizeof(char)<<endl ;
  cout<<" size of dou8ble = "<<sizeof(double)<<endl;
  cout<<"size of float = "<<sizeof(float)<<endl ;
  
  int firstnumber , secondnumber , multiplication_of_twonumbers ;
  cout<<"enter two number: " ;
  cin>> firstnumber>>secondnumber ;
  multiplication_of_twonumbers = firstnumber * secondnumber ;
  cout<< firstnumber<< " * "<< secondnumber<< " = " << multiplication_of_twonumbers ;
}  
