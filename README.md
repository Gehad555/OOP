# Object Oriented Programming 
______
 * ### TABLE OF CONTENT:
~~~
   1.Introduction
   2.Objects
   3. Class
   4.Encapsulation
   5.Abstraction
   6.Inheritance
   7.Polymorphism
   ~~~
* ## Join The team To Watch the Session   (42j02g8)
* ## [Session](https://cisuezedu.sharepoint.com/sites/TROSE/_layouts/15/stream.aspx?id=%2Fsites%2FTROSE%2FShared%20Documents%2FOOP%20with%20cpp%2FRecordings%2FMeeting%20in%20_OOP%20with%20c%2B%2B_-20221219_190510-Meeting%20Recording.mp4)
* ## [Oop Comic](https://www.facebook.com/GDSCSuezCanalUniversity/photos/482295073245315)
___
* # Introduction to OOP :
   * ## Articles
      * ### [C++](https://www.geeksforgeeks.org/object-oriented-programming-in-cpp/#intro)
      * ### [Java](https://www.geeksforgeeks.org/classes-objects-java/)
    * ## Videos
      * ### [Concept](https://youtu.be/fK2lLVqc8UY)
      *  ### [C++](https://youtu.be/2ZIrInD95Us)
      * ### [Java](https://youtu.be/FaaM6uVbuJM)
 * ### Characteristics of an Object Oriented Programming 
<pre>

        <img src="https://media.geeksforgeeks.org/wp-content/uploads/OOPs-Concepts.jpg" width="300" > 
 </pre>
 ___

 * # Class and Object in C++ : 
   * ### Object :  is an instance of aclass .
   *  ### Class  :  template for the object  . 
~~~ c++
class person
{
    char name[20];
    int id;
public:
    void getdetails(){}
};
  
int main()
{
   person p1; // p1 is a object 
}
~~~
____

# Encapsulation :
 * ## Articles
      * ### [C++](https://www.geeksforgeeks.org/object-oriented-programming-in-cpp/#encapsulation)
      * ### [Java](https://www.geeksforgeeks.org/encapsulation-in-java/)
* ## Videos
    * ### [Concept](https://youtu.be/qP9-3LnMZsE)
    *  ### [C++](https://youtu.be/eNtsHReY1Hop)
    * ### [Java](https://youtube.com/playlist?list=PLCInYL3l2AagY7fFlhCrjpLiIFybW3yQv)
* #   Encapsulation  in C++ : 

<pre>
         <img src="https://media.geeksforgeeks.org/wp-content/uploads/Encapsulation-in-C-1.jpg" width="300"> 
 </pre>
 * #  c++ program to explain
 ~~~ c++
#include<iostream>
using namespace std;
 
class Encapsulation
{
    private:
        // data hidden from outside world
        int x;
         
    public:
        // function to set value of
        // variable x
        void set(int a)
        {
            x =a;
        }
         
        // function to return value of
        // variable x
        int get()
        {
            return x;
        }
};
// main function
int main()
{
    Encapsulation obj;
     
    obj.set(5);
     
    cout<<obj.get();
    return 0;
}
~~~
____

# Abstraction :
 * ## Articles
      * ### [C++](https://www.geeksforgeeks.org/object-oriented-programming-in-cpp/#abstraction)
      * ### [Java](https://www.geeksforgeeks.org/abstraction-in-java-2/)
* ## Videos
    * ### [Concept](https://youtu.be/dW4WhJZB99U)
    *  ### [C++](https://youtu.be/JJEYMKVWEuc)
    * ### [Java](https://youtu.be/Kp8o-j4FmF8)

 * ## Program to Demonstrate the    working of Abstraction :
     
 ~~~ c++
#include <iostream>
using namespace std;
 
class implementAbstraction {
private:
    int a, b;
 
public:
    // method to set values of
    // private members
    void set(int x, int y)
    {
        a = x;
        b = y;
    }
 
    void display()
    {
        cout << "a = " << a << endl;
        cout << "b = " << b << endl;
    }
};
 
int main()
{
    implementAbstraction obj;
    obj.set(10, 20);
    obj.display();
    return 0;
}
~~~
_____
  # Inheritance  :
   *  ## Articles
      * ### [C++](https://www.geeksforgeeks.org/object-oriented-programming-in-cpp/#inheritance)
      * ### [Java](https://www.geeksforgeeks.org/inheritance-in-java/)
   * ## Videos
      * ### [Concept](https://youtu.be/1XE_cfonjXU)
      * ### [C++ part1](https://youtu.be/zIo__kgxgqo)
      * ### [C++ part 2](https://youtu.be/kg5TIwmxlCc)
      * ### [Java part 1](https://youtu.be/vnzteHmCIg0)
     * ### [Java part 2](https://youtu.be/ltuACF2NCh0)
* # Inheritance in C++ : 
  <pre>
         <img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/20190501121513/inheritance.png" width="300"> 
 </pre>

  ### Syntax: 
~~~ c++
class  <derived_class_name> : <access-specifier> <base_class_name>
{
        //body
}
~~~
## define member function without argument within the class :
~~~ c++
#include<iostream>
using namespace std;
 
class Person
{
    int id;
    char name[100];
   
    public:
        void set_p()
        {
            cout<<"Enter the Id:";
            cin>>id;
            fflush(stdin);
            cout<<"Enter the Name:";
            cin.get(name,100);
        }
   
        void display_p()
        {
            cout<<endl<<id<<"\t"<<name<<"\t";
        }
};
 
class Student: private Person
{
    char course[50];
    int fee;
     
    public:
    void set_s()
        {
            set_p();
            cout<<"Enter the Course Name:";
            fflush(stdin);
            cin.getline(course,50);
            cout<<"Enter the Course Fee:";
            cin>>fee;
        }
         
        void display_s()
        {
            display_p();
            cout<<course<<"\t"<<fee<<endl;
        }
};
 
main()
{
    Student s;
    s.set_s();
    s.display_s();
    return 0;
}
~~~

___

 ## Polymorphism :
   *  ## Articles
      * ### [C++](https://www.geeksforgeeks.org/object-oriented-programming-in-cpp/#polymorphism)
      * ### [Java](https://www.geeksforgeeks.org/polymorphism-in-java/)
   * ## Videos
      * ### [Concept](https://youtu.be/1XE_cfonjXU)
      * ### [C++ part 1](https://youtu.be/5ZoKcGdQt3c)
      * ### [C++ part 2](https://youtu.be/JJEYMKVWEuc)
      * ### [Java part 1](https://youtu.be/bI1vqMrIGlQ)
      * ### [Java part 2](https://youtu.be/kBpkPU0zkNk)
  
* # Polymorphism in C++ : 
  <pre>
         <img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/20190501131135/polymorphism_example.png" width="300"> 
 </pre>

 * ## function overloading

 ~~~c++
using namespace std;
class Geeks {
public:
   
    // Function with 1 int parameter
    void func(int x)
    {
        cout << "value of x is " <<
                 x << endl;
    }
 
    // Function with same name but
    // 1 double parameter
    void func(double x)
    {
        cout << "value of x is " <<
                 x << endl;
    }
 
    // Function with same name and
    // 2 int parameters
    void func(int x, int y)
    {
        cout << "value of x and y is " <<
                 x << ", " << y << endl;
    }
};
 
// Driver code
int main()
{
    Geeks obj1;
 
    // Function being called depends
    // on the parameters passed
    // func() is called with int value
    obj1.func(7);
 
    // func() is called with double value
    obj1.func(9.132);
 
    // func() is called with 2 int values
    obj1.func(85, 64);
    return 0;
}
~~~ 
 ### C++ program for function overriding
~~~ c++
#include <bits/stdc++.h>
using namespace std;
 
class base {
public:
    virtual void print()
    {
        cout << "print base class" <<
                 endl;
    }
 
    void show()
    {
      cout << "show base class" <<
               endl;
    }
};
 
class derived : public base {
public:
   
    // print () is already virtual function in
    // derived class, we could also declared as
    // virtual void print () explicitly
    void print()    
    {
        cout << "print derived class" <<
                 endl;
    }
 
    void show()
    {
      cout << "show derived class" <<
               endl;
    }
};
 
// Driver code
int main()
{
    base* bptr;
    derived d;
    bptr = &d;
 
    // Virtual function, binded at
    // runtime (Runtime polymorphism)
    bptr->print();
 
    // Non-virtual function, binded
    // at compile time
    bptr->show();
 
    return 0;
}
~~~
___

