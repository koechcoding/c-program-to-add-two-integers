#cpp-program-to-add-two-integers
#include<iostream>
using namespace std;

int main(){
    int first_num, second_num, sum;
    cout<< "enter the values of the two integers: ";
    cin>> first_num>> second_num;
    sum = first_num + second_num;

    //print sum
    cout<< first_num << " + " << second_num << " = " << sum ;
    return 0;
}