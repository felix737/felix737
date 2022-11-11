#include <iostream>
using namespace std;

int main() {
    // I variabili delle varie figure geometriche
    float a=0;
    float b=0;
    float c=0;
    cin >> a >> b >> c;
    // scrivo ogni operazione riguardante l'aerea di ogni figura geometrica richiesta
    float areadiuntriangolo = (a*b)/2;
    float aereadiunquadrato = a*b;
    float areadiunrettangolo = a*b;
    float areadiuntrapezio =(a+b)*c/2;
    std::cout << "Areadiuntriangolo" << std::endl;
    std::cout << "Areadiunquadrato" << std::endl;
    std::cout << "Areadiunrettangolo" << std::endl;
    std::cout << "Areadiuntrapezio" << std::endl;
    return 0;
