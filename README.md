# Student-system-Cpp
A simple program that asks for student details and displays them.
#include <iostream>
using namespace std;
int main(){
    string studentName, regNo;
    float num1,num2,num3,num4, Avg;

    cout<<"Enter the student name:"<<endl;
    getline (cin,studentName);
    cout<<"Enter your registration number:"<<endl;
    getline (cin,regNo);
    cout<<"Enter marks in the first subject:";
    cin>>num1;
    cout<<"Enter marks in the second subject:";
    cin>>num2;
    cout<<"Enter marks in the third subject:";
    cin>>num3;
    cout<<"Enter marks in the fourth subject:";
    cin>>num4;

    Avg=(num1+num2+num3+num4)/4;
    cout<<"Studentname:"<<studentName<<endl;
    cout<<"Registration number:"<<regNo<<endl;
    cout<<"Subject scores:"<<endl;
    cout<<"Subject 1:"<<num1<<endl;
    cout<<"Subject 2:"<<num2<<endl;
    cout<<"Subject 3:"<<num3<<endl;
    cout<<"Subject 4:"<<num4<<endl;
    cout<<"The average is:"<<Avg<<endl;
    return 0;
}
