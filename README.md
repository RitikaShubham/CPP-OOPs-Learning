# CPP-OOPs-Learning
My daily learning journey of Object-Oriented Programming in C++ with examples and notes.

## 📅 Daily Progress

### ✅ Day 1 - [Date]
- ✔️ What I Learned:
  - What is OOP?
  - Why use OOP?
  - 4 Pillars of OOP: Encapsulation, Inheritance, Polymorphism, Abstraction

- ✔️ Code Practiced:
  - Created a basic class and object
  - Example of Encapsulation

> 📁 Check the folder: `Day1_OOP_Basics/`

---

## 📌 Topics Covered (So Far)
- [x] Introduction to OOP
- [x] Classes and Objects
- [ ] Constructors and Destructors
- [ ] Inheritance
- [ ] Polymorphism (Compile-time and Run-time)
- [ ] Abstraction
- [ ] Encapsulation
- [ ] Virtual Functions
- [ ] OOPs in DSA Problems


#include <iostream>
using namespace std;

class Student{   // class created 
    private:

    string Name;    // data members 
    int Age;
    int Height;

    public:

        int getAge(){      // functions 
        return this->Age;
    }
};


class Human {

    public:
        int Age;
        int Height;
        int Weight;

    public:

    int getAge(){
        return this->Age;
    }

    int setHeight( int h ){
         return this->Height = h;
    }
};
 // syntax of inheritance 
 // class name (child) : access mode (p/p/g) parent class {}

class Male : public Human {
 public:
     string color;
}

int main(){

    Male object1;
    object1.color;
}


