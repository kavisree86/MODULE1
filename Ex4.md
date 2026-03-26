# Ex.No:4
# Ex.Name:Write a C++ program to find the maximum of two numbers between 95, 64 and maximum of three numbers between 22,28,21 using constructor overloading.
## Date:
## Aim:
To write a C++ program to compute the quotient and remainder using class methods defined outside the class.





## Algorithm:

Start the program.
Define a class Division with two member functions: -computeQuotient(int a, int b) -computeRemainder(int a, int b)
Declare these functions inside the class but define them outside using scope resolution ::.
In the main() function, read two integers from the user (dividend and divisor).
Call the methods using the class object to compute quotient and remainder.



## Program:
```

#include <iostream>
using namespace std;
class view{
    public:
    void remain(int a,int b);
};
void view::remain(int a,int b)
{
    cout<<"The quotient of the division is:"<<a/b<<endl;
    cout<<"The remainder of the division is:"<<a%b;
}
int main()
{
    int a,b;
    cin>>a>>b;
    view v;
    v.remain(a,b);
}
```

## Output:

<img width="621" height="252" alt="image" src="https://github.com/user-attachments/assets/4ce9e7e3-ac4d-48fe-9268-d79593eb115c" />


## Result:
The program successfully computes the quotient and remainder using class methods defined outside the class in C++.
