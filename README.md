# Experiment 2
## Aim-
To study and implement C++ program(Data types)

## Theory-
Understanding the size of various data types is crucial for memory management and optimization in programming. 
Different data types (e.g., int,short int,long int,float, double,long double,bool,char,auto,register) occupy different amounts of memory.
and checking of size of some data types given by user.

## Int data type:-
In programming, the int data type is used to represent integer values, which are whole numbers without a fractional part.

For example:
- In Python, the int type can represent arbitrarily large numbers, limited only by the amount of available memory, as Python automatically handles larger integers with its built-in int type.

The int type is fundamental in programming for performing arithmetic operations, loops, indexing arrays, and more.

## Float data type:-
The float data type is used to represent real numbers with fractional parts, allowing for the representation of both whole and decimal numbers. 

The range of values for a 32-bit float is roughly from \(1.4 \times 10^{-45}\) to \(3.4 \times 10^{38}\).

Floats support arithmetic operations like addition, subtraction, multiplication, and division.

Floats are widely used in scientific calculations, graphics, simulations, and any application requiring real-number arithmetic.

## Double data type:-
The double data type is used to represent double-precision floating-point numbers. It provides greater precision and a larger range than the float data type. Double-precision floating-point format is also based on the IEEE 754 standard, typically using 64 bits.

The range of values for a 64-bit double is roughly from \(5 \times 10^{-324}\) to \(1.7 \times 10^{308}\).

Doubles support all the same arithmetic operations as floats (addition, subtraction, multiplication, division).


## Code - 
### 1.
```
//subham
//23070123132
//entc b2
//experiment 2
#include<iostream>
using namespace std;
int main(){
    cout<< "size of char: " <<sizeof(char) << "byte(s)" <<endl;
     cout<< "size of int: " <<sizeof(int)<< "byte(s)" <<endl;
     cout<< "size of short int: " <<sizeof(short int) << "byte(s)" <<endl;
     cout<< "size of long int: " <<sizeof(long int) << "byte(s)" <<endl;
     cout<< "size of float : " <<sizeof(float) << "byte(s)" <<endl;
     cout<< "size of double: " <<sizeof(double) << "byte(s)" <<endl;
     cout<< "size of long double: " <<sizeof(long double) << "byte(s)" <<endl;
     cout<< "size of bool: " <<sizeof(bool) << "byte(s)" <<endl;
     return 0;
}
```

### 2.
```
//subham
//23070123132
//entc b2
//experiment 2
#include<iostream>
using namespace std;
int main()
{
    int a;
    cout<<"enter any integer:";
    cin>>a;
    cout<<"\ninteger ="<<a<<" and size is "<<sizeof(a)<< "bytes";
    float b;
    cout<<"\nenter a number:";
    cin>>b;
    cout<<"\nfloat ="<<b<<" and size is "<<sizeof(b)<< "bytes";
    short int c;
    cout<<"\nenter an integer:";
    cin>>c;
    cout<<"\nshort integer ="<<c<<" and size is"<<sizeof(c)<< "bytes";
    return 0;
}
```

### 3.
```
//subham
//23070123132
//entc b2
//experiment 2
#include<iostream>
using namespace std;
int main()
{
    int a;
    cout<<"enter any integer:";
    cin>>a;
    cout<<"\ninteger ="<<a<<" and size is "<<sizeof(a)<< "bytes";
    float b;
    cout<<"\nenter a number:";
    cin>>b;
    cout<<"\nfloat ="<<b<<" and size is "<<sizeof(b)<< "bytes";
    short int c;
    cout<<"\nenter an integer:";
    cin>>c;
    cout<<"\nshort integer ="<<c<<" and size is"<<sizeof(c)<< "bytes";
    return 0;
}
```

## Explanation - 
The program uses the sizeof operator to determine and display the size of various data types in bytes. It includes common data types such as int, float, double, char,bool,register,auto,short int,long int,long double and others.

## Output-
### 1.
![Screenshot 2024-07-30 224910](https://github.com/user-attachments/assets/30f8b52b-e3ff-429e-a68f-e46d004d86b1)
### 2.
![Screenshot 2024-07-30 225050](https://github.com/user-attachments/assets/444ab374-1c7f-4100-af10-846ba0a8464a)
### 3.
![Screenshot 2024-07-31 100404](https://github.com/user-attachments/assets/af8c1443-8f0a-4b65-b127-50ad76488a55)

## Conclusion - 
This program helps in understanding how much memory is allocated for different data types, which is important for writing efficient and optimized code.
