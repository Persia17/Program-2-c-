# Program-2-c++-

#include <iostream>
using namespace std;
struct point
{
    int x, y;
}; 
int main()
{
    point p1, p2, p3;
    cout << "Enter the coordinates of point 1:" << endl;
    cin >> p1.x >> p1.y;
    cout << "Enter the coordinates of point 2:" << endl;
    cin >> p2.x >> p2.y;
    p3.x=p1.x+p2.x;
    p3.y=p1.y+p2.y;
    cout<<"the coordinates of point 3:"<<"("<<p3.x<<","<<p3.y<<")";
}
