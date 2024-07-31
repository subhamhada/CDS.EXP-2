# Experiment 2
## Aim-
write a C++ program that determines the size of different data types.

## Theory-
Understanding the size of various data types is crucial for memory management and optimization in programming. 
Different data types (e.g., int,short int,long int,float, double,long double,bool,char,auto,register) occupy different amounts of memory.
and checking of size of some data types given by user.

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

## Conclusion - 
This program helps in understanding how much memory is allocated for different data types, which is important for writing efficient and optimized code.
