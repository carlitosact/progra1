# progra1// prog.cpp : Defines the entry point for the console application.
//

#include "stdafx.h"
#include <iostream>
#include "conio.h"
#include "stdlib.h"//para usar system

using namespace std;

void main()
{  
	float NP,P1,P2,P3,PF,promedio,NF;
	int NR,i;
	char resp;// declarar una variable que acepta letras 
	promedio=0;
	i=0;

	do { 
		cout<<"ingrese las notas prscticas "<<endl;
		cin >> NP;
		cout<<"ingrese la nota del primer parcial"<<endl;
		cin>> P1;
		cout<<"ingrese la nota del segundo parcial"<<endl,
		cin>> P2;
		cout<<"ingrese la nota del tercer parcial"<<endl;
		cin>> P3;
		cout<<"ingrese la nota final"<<endl;
		cin>> PF;
		NF=(NP*0.2)+((P1+P2+P3)/3)*0.4+PF*0.4;
		promedio=promedio+NF;
		
		i++;
		    cout<<"desea continuar: (n para finalizar )"<<endl;
			cin>>resp;
			system("cls");
	}while (resp != n);
	 getch();


