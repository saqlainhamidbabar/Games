# Games
small mathematical games
#include <iostream>
//game for guess a number
using namespace std;
int main(){
	int num;
	//here we get a input from user to make program friendly
	cout<<"Guess a Number : ";
	cin>>num;
	//we use if and else statement in program
	if(num>10 && num<100)
	cout<<"\n Whats a true guess!";
	else
	cout<<"\nOpps! try next time.................. ";
	cout<<endl;
	
	return 0;
}
