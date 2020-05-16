# banking.cpp
How saving and current account works
#include<conio.h>
#include<iostream.h>
class bank {
public:
int balance;
float credit;
float debit;
private:
void saving();
void debit();
void bal();
};
void bank::saving()
{
cout<<"enter the total balance";
cin>>balance;
cout<<"Initial balance="<<balance;
}
void bank::debit()
{
cout<<"Enter 

