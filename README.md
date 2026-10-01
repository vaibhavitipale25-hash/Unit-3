Experiment: Fundamentals of Object-Oriented Programming

Name: Vaibhavi Tipale
Roll No.: AD2172
Course: Object-Oriented Programming with C++
Unit: Polymorphism

Aim

To study and implement the fundamental concepts of Object-Oriented Programming (OOP) using C++.

Theory

Object-Oriented Programming (OOP) is a programming paradigm that organizes software design around objects rather than functions and logic. The main features of OOP are:

1. Class – A blueprint for creating objects.
2. Object – An instance of a class.
3. Encapsulation – Wrapping data and methods into a single unit.
4. Abstraction – Hiding implementation details and showing only essential features.
5. Inheritance – Acquiring properties and behaviors of an existing class.
6. Polymorphism – Ability of an object to take many forms.

Program

#include <iostream>
using namespace std;

class Student {
private:
    string name;
    int rollNo;

public:
    void setData(string n, int r) {
        name = n;
        rollNo = r;
    }

    void displayData() {
        cout << "Name: " << name << endl;
        cout << "Roll No: " << rollNo << endl;
    }
};

int main() {
    Student s1;
    s1.setData("Vaibhavi Tipale", 2172);
    s1.displayData();

    return 0;
}

Output

Name: Vaibhavi Tipale
Roll No: 2172

Conclusion

Thus, the basic concepts of Object-Oriented Programming such as class, object, data members, and member functions were successfully implemented using C++.
