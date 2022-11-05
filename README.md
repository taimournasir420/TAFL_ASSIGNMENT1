# TAFL_ASSIGNMENT1
ASSIGNMENT1-FA20BSCS056


#include<iostream>
using namespace std;

//FIGURE 1 
int main()
{
	int n1=1;
	int n2=2;
	int size;
	int comb[size];
	
	cout<<"FIGURE 1 : Input a combination of 1s and 0s to see if the DFA accepts it or not: "<<endl;
	cout<<"First input the size of your combination: ";
	cin>>size;
	cout<<"Now input your combination: ";
	for(int index=0;index<size;i++)
	{
		cin>>comb[size];
	}
	
	
		if(comb[size]==0)
		{
			cout<<"Combination not accepted";
		}
		else
		{
			cout<<"Combination is accepted";
		}
	
	

	
}











#include<iostream>
using namespace std;

//FIGURE 2
int main()
{
int size;
	int comb[size];
	
	cout<<"FIGURE 2 : Input a combination of 1s and 0s to see if the DFA accepts it or not: "<<endl;
	cout<<"First input the size of your combination: ";
	cin>>size;
	cout<<"Now input your combination: ";
	for(int i=0;i<size;i++)
	{
		cin>>comb[i];
	}

	
	        if((comb[0]==0 && comb[1]==1) || (comb[1]==0 && comb[0]==1))
		{
			cout<<"Combination not accepted";
		}
		else
		{
			cout<<"Combination is accepted";
		}
    
}
