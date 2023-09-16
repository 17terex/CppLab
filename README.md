# CppLab

'''
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
'''
