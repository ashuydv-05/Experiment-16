# Experiment-16
c plus plus and data structures experiment 16

AIM:- to study and implement exceptional handeling

Software Used:-VS code

Theory:-Exception handling in C++ provides a mechanism to handle runtime errors, ensuring smooth program flow. Key components include try, catch, and throw. The try block contains code that may throw an exception. The throw statement signals an error by "throwing" an exception object. The catch block handles this exception based on its type. Multiple catch blocks can be used to manage different types of exceptions. C++ supports various exception types, such as built-in types (int, char) or user-defined types (class). Using std::exception as a base class allows uniform handling of exceptions. Uncaught exceptions cause program termination unless caught.

code:
```
//AshuYadav
//23070123154

#include <iostream>
using namespace std;

int main() 
{
    int den,num;
    float ans;

    cout << "Enter the numerator: ";
    cin >> num;
    cout << "Enter the denominator: ";
    cin >> den;

    try 
    {
        if (den == 0) 
        {
            throw 0;  
        }

        cout << "Answer: "<< num/den << endl;
    }

    catch (int x) 
    {
        cout << "ERROR: DIVISION BY ZERO" << endl;
    }

}
```
![exp16](https://github.com/ashuydv-05/Experiment-16/blob/main/Screenshot%202024-10-22%20070942.png)

Conclusion:- In this experiment we learnt about exceptional handling and its keywords

