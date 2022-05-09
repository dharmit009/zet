# Use increments and decrements in C++ carefully:

Write what you think the output should be and then Run this code!

```
#include <iostream>
using namespace std;

int main(){

    int x = 10;
    int y = ++x;

    cout<<"Operations Performed:\nx=10\ny=++x"<<endl;
    cout<<"x: "<<x<<endl;
    cout<<"y: "<<y<<endl;
    cout<<endl;

    int a = 10;
    int b = a++;

    cout<<"Operations Performed:\na=10\nb=a++"<<endl;
    cout<<"a: "<<a<<endl;
    cout<<"b: "<<b<<endl;

    return 0;
}

```

    c++ challenge increment decrement
