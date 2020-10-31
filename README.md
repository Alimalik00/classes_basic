# classes_basic
A basic class program for input and display

#include<iostream>
#include<conio.h>
#include<math.h>
using namespace std;
class point {
private: 
int x, y; 
public:
point() 
{
	x = 0; 
	y = 0;
}
point(int A, int B) 
{
x = A;
y = B;
}
void setX(int A)
{ 
x = A; 
}
void setY(int B) 
{
y = B; 
}
int getX() 
{
return x; 
}
int getY()
{ 
return y;
}
void display()
{
cout << "Coordinates are :  " << x << " , " << y  << endl;
}
};
void main()
{ point A, B;
cout << "1st point  ";
A.display();
cout << "2nd point  "; 
B.display();
A.setX(10); 
A.setY(20);
B.setX(30); 
B.setY(40);
cout << endl<<" new values : " << endl;
cout << "1st value ";
A.display();
cout << "2nd value "; 
B.display();
cout <<endl<< "Addition of cordinate points : " << A.getX() + B.getX() << ", " << A.getY() + B.getY()  << endl; 

}
