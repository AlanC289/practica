Funciones matemáticas c++

#include <iostream>
#include<cmath>
using namespace std;

int main()
{
    double x = 3;
    double y= 4;
    double z,f;
    
    z=pow(2,3);  //pow(2,3)--> eleva una base a una potencia dada (2 elevado a la 3)
    f= sqrt(9); // sqrt()--> raizcudrada
     //abs()--> valor absoluto
     //round()-->redondea el valor dado al numero mas cercano
     //ceil()--> redondea siempre hacia arriba
     //floor()--> redondea siempre hacia abajo
    
    cout<<z<<endl;
    cout<<f;
    
    

    return 0;
}
