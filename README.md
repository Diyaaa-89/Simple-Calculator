# Simple-Calculator

#include<iostream>

using namespace std;
 int main()
 {
 	int num1, num2, result;
 	char op;
 	
 	
 	
 	cout<<"Enter num1 value:";
 	cin>>num1;
 	
 	cout<<" Enter num2 value:";
 	cin>>num2;
 	
 	cout<<" Enter any operator: +, -, *, / : ";
 	cin>>op;
 	
 	switch (op)
 	{
 		case '+' :
 			cout <<num1 <<"+" <<num2 <<"="<<(num1+num2);
 			break;
 		
 		case '-' :
 			cout <<num1 <<"-" <<num2 <<"="<<(num1-num2);
 			break;
 			
 		case '*':	
 			cout <<num1 <<"*" <<num2 <<"="<<(num1*num2);
 			break;
 			
 		case '/':
 			cout <<num1 <<"+" <<num2 <<"="<<(num1/num2);
 			break;
 			
		default:
			cout <<"Invalid Operator !!";
	}
	return 0;
 }
