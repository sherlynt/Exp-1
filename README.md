# Exp-1

AIM: To install Visual Studio Code and writing a program to print hello world, and calculator program

SOFTWARE: Visual Studio Code

Theory: 
VS code is a code editor that, with the appropriate extensions, can run all types of programs and codes. 

In the codes, MinGW is used to add the c++ extension printing hello world uses the "cout" character output, and the calculator program uses the arithmetic operators sum(+), difference(-), multiplication(*), and division(/).

1) Installation of VS code

   
 a)Use chrome to search for VS code installation
   

 
 b)Click on "I accept agreement" of the pop up which will appear and then click on next.



c)VS code installation will start



2) Downloading MinGW for compilation 



a) A pop up window will appear.Click on install.



b) Click all the required boxes for the C and C++ language.



c)Go to This PC, open MinGW folder, click on bin folder, a number of files will appear and then copy its path.


d) In This PC, click on advanced settings, a pop up window will appear, where clikc on Environmental variables.

e) Click on New and then paste the copied path. Then click OK.

f)All changes are applied and you can use MinGW.

THEORY:

This C++ application uses the iostream library to perform input and output operations while demonstrating fundamental programming concepts. 

It contains a C++ program's structure, with the main function serving as the entry point. After asking the user to enter two integers, the software uses simple arithmetic operations to calculate and display the values of their total, difference, product, and quotient. 

It shows how to use cin to read user input and cout to display the results.


Hello World:

```
#include <iostream>
using namespace std;
int main() {
   cout << "Hello World"; 
   return 0;
}
```

Output:![image](https://github.com/user-attachments/assets/3fc2259e-d466-4b2a-9f35-e963deee721e)



Calculator:
```
#include <iostream>
using namespace std;
int main()
{
    int a,b,sum=0,diff=0,prod=0,q=0;
    cout<<"Enter the first no.:";
    cin>>a;
    cout<<"Enter the second no.:";
    cin>>b;
   
    sum=a+b;
    cout<<"Sum of the given nos. is:"<<sum<<endl;
     diff=a-b;
    cout<<"Difference of the given nos. is:"<<diff<<endl;
     prod=a*b;
    cout<<"Product of the given nos. is:"<<prod<<endl;
     q=a/b;
    cout<<"Division of the given nos. is:"<<q<<endl;
   
}
```
Output: ![image](https://github.com/user-attachments/assets/690ebeb5-4f2d-471d-8d0b-51c46ff74848)



CONCLUSION:

VS code is a versatile,powerful and user friendly code editor. Along with it, installing MinGW offers essential compiling tools for C and C++. It has a straight forward installing process and is a reliable and efficient compiler for Windows.

Basic concepts like receiving user input, using namespaces, including libraries, and performing arithmetic operations are all combined in the above C++ program. It offers an actual example of basic C++ programming and user interaction by showing how to calculate and display the sum, difference, product, and quotient of two integers.
