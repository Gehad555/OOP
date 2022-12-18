# Object Oriented Programming 

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

        <img src="https://media.geeksforgeeks.org/wp-content/uploads/OOPs-Concepts.jpg" width="300"> 
 </pre>
 ___

 * # Class and Object in C++ : 
   * ### Object :  is an instance of aclass .
   *  ### Class  :  template for the object  . 
<pre>
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
</pre>
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
___
____
# Abstraction :
 * ## Articles
      * ### [C++](https://www.geeksforgeeks.org/object-oriented-programming-in-cpp/#abstraction)
      * ### [Java](https://www.geeksforgeeks.org/abstraction-in-java-2/)
* ## Videos
    * ### [Concept](https://youtu.be/dW4WhJZB99U)
    *  ### [C++](https://youtu.be/JJEYMKVWEuc)
    * ### [Java](https://youtu.be/Kp8o-j4FmF8)

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
         <img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/20190501121513/inheritance.png"width="300"> 
 </pre>

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
         <img src="https://media.geeksforgeeks.org/wp-content/cdn-uploads/20190501131135/polymorphism_example.png"width="300"> 
 </pre>

______

