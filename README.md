# Yadira-Carballo-
Códigos 
#include<iostream>
#include<cmath>
using namespace std;
int main (){
	//definimos las variables
	double teta=45;
	double phy=45;
	double r=10;
	double z=0;
	double y=0;
	double x=0;
	//ecuaciones

#include<iostream>
#include<cmath>
using namespace std;
int main (){
	float X1=3;
	float X2=-7;
	float Y1=-5;
	float Y2=6;
	float Z1=2;
	float Z2=-4;
	float P1P2=0;
	P1P2=sqrt(((X2-X1)*(X2-X1))+((Y2-Y1)+(Y2-Y1))+((Z2-Z1)*(Z2-Z1)));
	cout<<P1P2;
}
#include<iostream>
#include<cmath>
using namespace std;
#define PI 3.14159

int main(){
	//definimos las variables
	float teta=0;
	float phy=0;
	float r=0;
	float x=0;
	float y=0;
	float z=0;
	//Ecuaciones
	x=r*sin(phy)*cos(teta);
	y=r*sin(phy)*sin(teta);
	z=r*cos(phy);
	cout<<"("<<x>>","<<y>>","<<z>>")">>;
	return 0;
}

