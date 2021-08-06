#include<iostream>
#include<windows.h>

using namespace std;

void ShowMenu()
{
	cout<<"=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=\n";
	cout<<"=*=*=*=*=*=*=*=*=*=*=*=# QUIZ #=*=*=*=*=*=*=*=*=*=*=*=*=\n";
	cout<<"=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=\n\n\n\n\n\n\n\n";
	
	cout<<"1. NEW QUIZ"<<endl<<"2. HIGHEST SCORE"<<endl<<"3. EXIT"<<endl<<endl<<endl;
	}
int main()
{
	system("COLOR 57 ");
	string questions[10]={
	" Q.1 C++ was developed by ",
	"Q.2  Which of the followingis a keyword",
	"Q.3 ___ is the smalllest individual limit in a program.",
	"Q.4 What is a constant that contains a single character enclosed with single quotes?",
	"Q.5 The modulus operators uses____chracter.",
	"Q.6 Every variable shuold be seperated by___seperator.",
	"Q.7 Auto,statics , extern and register are callled as___.",
	"Q.8 How many storage specifies are there in a C++?",
	"Q.9 Singned ,unsigned , long and short are some of the ___",
	"Q.10 Logical AND (&&) and Logical OR are___ operators."
	};

string options[10]={
"1. Thomas Kushz	2. John kemney	3.Bjarne Stroutstrup 	4. James Goiling",
"1. Size	2. Key	3. Jump	 4.Switch",
"1. Variable	2. Control	3.  Character		4. Token",
"1. Character	2. Numeric	3. Fixed	4. Floating point",
"1. +	2. *	3. / 4. %",
"1. Dot	2. Colon	3. Comma	4. Semicolon",
"1. Static	2. Register	3. Auto	4. Storage specifier",
"1. 2  2. 3 	3. 4	4. 5 ",
"1. Void	2. L Data		3. Derived data		4. Modifiers ",
"1. Logical	2. Equality	3. Class member		4. Comma"
};

int ans[10]={3, 4, 4, 1, 4, 3, 4, 3, 4, 1 };

string PlayerName;

int highestScore =0;

char ch='y';

while(ch=='y')
{
	int CurrentResult=0;
	string CurrentPlayer;
	system("CLS");
	ShowMenu();
	int menu;
	cin>>menu;
	
	switch(menu)
	{
		case 1:
			

			cout<<"ENTER YOUR NAME: "<<endl<<endl;
			cin>>CurrentPlayer;
			
			for(int i=0; i<10; i++){
			system("COLOR 37");
			system("CLS");
			cout<<"=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=\n";
			cout<<"=*=*=*=*=*=*=*=*=*=*=*=# QUIZ START #=*=*=*=*=*=*=*=*=*=*=*=\n";
			cout<<"=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=\n\n\n\n\n\n\n\n";
				int op;
				cout<<questions[i]<<endl<<endl;
				cout<<options[i]<<endl<<endl;
				cout<<"Enter options: ";
				cin>>op;
				if(op==ans[i]){
					CurrentResult++;
					if(CurrentResult>highestScore){
						highestScore=CurrentResult;
						PlayerName=CurrentPlayer;
						}
				}
			}
			cout<<"\n\n\n"<<"==*==*==//==*==*==\n\n"<<"YOUR SCORE: "<<CurrentResult<<endl;
			break;
			
			case 2:
			system("COLOR F9");
			cout<<"=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=\n";
			cout<<"=*=*=*=*=*=*=*=*=*=*=*=# HIGHEST SCORE #=*=*=*=*=*=*=*=*=*=*=\n";
			cout<<"=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=*=\n\n\n\n\n";
			cout<<"Highest Score: "<< highestScore<<" By "<<PlayerName<<endl<<endl;
			break;
			
			case 3:
			system("COLOR 64");
			cout<<"THANK YOU for using this App...";
			exit(0);
			break;
			default:
			cout<<"Wrong Selection";
				
	}
	
	cout<<"Do you want to continue y/n ?";
	cin>>ch;
	}
}


