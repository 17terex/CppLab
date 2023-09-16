# CppLab

`
#include <iostream>
using namespace std;

int main ()
{
    float dist,totalp,pet,pricep;
    cout<<"Vvedite rasstoyanie v km";
    cin>>dist;
    cout<<endl;
    
    cout<<"Vvedite rashod benzina v litrah/100km";
    cin>>pet;
    cout<<"\n";
    
    cout<<"Vvedite stoimost benzina";
    cin>>pricep;
    cout<<"\n";
    
    totalp = (((dist*pet)/100)*pricep)*2;
    
    cout<<"Poezdka oboidetsya v "<<totalp<<" rublei \n";
    cout<<"\n";
}
`

IGRA UGADAI CHISLO
`
#include <iostream>
#include <conio.h>
using namespace std;

int main(int argc, char* argv[])
{
    int a, n;
    n = rand() % 100+1;
    
    do {
        cout<< "Vvedite chislo:";
        cin>>a;
        if( a > n)
        {
            cout<<"Menshe"<<endl;
        } else if(a < n){
            cout<<"Bolshe"<<endl;
        }
    }
    while (a != n);
    cout<<"Pravilno"<<endl;
    getch();
}
`
