#include<bits/stdc++.h>
using namespace std;
int main(){
	cout<<"欢迎来到乘法计算游戏！一开始题目还比较简单，后面就难了,加油"<<endl ;
	srand(time(0)); 
	long long a=0,s=rand()%10,d=rand()%10,r;
	char zie;
	srand(time(0));
	int w=  rand()%10;
	int u= rand()%10; 
	
	system("color 4");
	for(int i=1;;i++){
		cout<<"你的分数："<<a<<endl; 
		s+=w;
		d+=u;
		 
		cout<<"第"<<i<<"题:"<< s<<"×"<<d<<"=";
		cin>>r;
		if(r==s*d){
			cout<<"答对了！要继续吗，要就输入y，不要就输入e"<<endl; 
			cin>>zie;
			a++;
				system("cls");
			if(zie=='y'){
				continue;
					system("cls");
			}
			else{
				break;
				
			}
			system("cls");
			
		}
		else{
			cout<<"答错了！应该是"<<s*d<<"。"<<"要继续吗，要就输入y，不要就输入e"<<endl; 
			cin>>zie;
				system("cls");
			if(zie=='y'){
				continue;
					system("cls");
			}
			else{
				break;
			}
			system("cls");
		}
			system("cls");
		 
	}
return 0;
}

