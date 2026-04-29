#include <iostream>
#include <iomanip>
#include <cmath>

using namespace std;

int main(){

cout << "Sibongile Matshona " << endl;
cout << "sim0070 sisiematshona@my.und.edu" << endl;
cout << "Department of Computer Science and Engineering" << endl;
cout << "CSCE 1030.003" << endl;



// constants

const double GRAVITY = 9.8;
const double PI = 3.14159;

// variables

long int buoyantForce;
double density;
double volume;
double radius;

// Input the density and the buoyant force

cout << "Please enter the density of the liquid: ";
cin >> density;

cout << "Please enter the buoyant force of the object: ";
cin >> buoyantForce;

// calculate volume

volume = buoyantForce / (density * GRAVITY);

// Output the volume in 3 decimal places

cout << fixed << setprecision(3) << "The volume of the sphere is " << volume << " meters cubed" << endl;

// calculate radius

radius = cbrt((3 * volume) / (4 * PI));

// Output the radius in 2 decimal places

cout << fixed << setprecision(2) << "The radius of the sphere is " << radius << " meters" << endl;


return 0;
}
