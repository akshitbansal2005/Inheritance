# Inheritance
Here’s a markdown version of the content with improved formatting:

```markdown
# Study and Implementation of Inheritance

## Aim:
To study and implement Inheritance in Object-Oriented Programming.

## Software Used:
- VS Code
- Dev C++

## Theory:

### Inheritance Definition:
The capability of a class to derive properties and characteristics from another class is called **Inheritance**. It is a fundamental feature of Object-Oriented Programming. Inheritance allows new classes (derived/child classes) to be created from existing classes (base/parent classes).

### Syntax of Inheritance:
```cpp
class derived_class_name : access_specifier base_class_name {
    // body
};
```

## Properties of Constructors:
Inheritance allows a class (child) to inherit properties and behaviors (methods) from another class (parent). Here are the key properties:

1. **Code Reusability**: Use methods and attributes of a base class in derived classes.
2. **Method Overriding**: Override base class methods in derived classes.
3. **Access Control**: Different inheritance types (public, protected, private) affect access to base class members.
4. **Hierarchical Structure**: Inheritance creates a class hierarchy.
5. **Abstract Classes and Interfaces**: Base classes can define contracts through abstract methods.
6. **Virtual Functions and Polymorphism**: Inheritance enables polymorphism through base class pointers or references.

## Advantages of Inheritance:
1. **Code Reusability**: Reduces redundancy.
2. **Modularity**: Each class can be maintained independently.
3. **Improved Maintainability**: Changes in the base class propagate to derived classes.
4. **Enhanced Functionality**: Derived classes can extend or modify base class methods.
5. **Polymorphism**: Base class references can interact with derived class objects.
6. **Easier Testing and Debugging**: Clear hierarchy simplifies testing.
7. **Clearer Relationships**: Intuitive modeling of real-world relationships.
8. **Encapsulation and Abstraction**: Hides complexity and exposes simpler interfaces.

## Types of Inheritance:

### 1. Single Inheritance:
A derived class inherits from one base class.
```cpp
class A { ... };
class B : public A { ... };
```

### 2. Multiple Inheritance:
A derived class inherits from more than one base class.
```cpp
class A { ... };
class B { ... };
class C : public A, public B { ... };
```

### 3. Multilevel Inheritance:
A class inherits from another derived class.
```cpp
class A { ... };
class B : public A { ... };
class C : public B { ... };
```

### 4. Hierarchical Inheritance:
Multiple derived classes inherit from a single base class.
```cpp
class A { ... };
class B : public A { ... };
class C : public A { ... };
```

## Algorithms

### 1. Simple Inheritance Algorithm:
1. Define class `Uni` with:
    - A string `uni = "Symbiosis: "`
    - A method `discipline()` to print "Engineering"
2. Define class `Dep` inheriting from `Uni` with:
    - A string `dept = "Electronics & Communication"`
3. In `main()`:
    - Instantiate object `u1` of class `Dep`
    - Call `discipline()` on `u1`
    - Print `u1.uni + u1.dept`

### 2. Multiple Inheritance Algorithm:
1. Define class `Vehicle` with:
    - A string `company = "Ford"`
    - A method `type()` to print "Mustang"
2. Define class `Specs` with:
    - A string `mileage = "8 kmpl"`
    - A method `colour()` to print "Grey"
3. Define class `Car` inheriting from both `Vehicle` and `Specs` with:
    - A string `seater = "4 seater"`
4. In `main()`:
    - Instantiate object `f2` of class `Car`
    - Call `colour()`
    - Print `f2.company`, `f2.type()`, `f2.seater`, `f2.mileage`

### 3. Multilevel Inheritance Algorithm:
1. Define class `Food` with:
    - A string `cuisine = "Indian"`
    - A method `type()` to print "Asian"
2. Define class `Dish` inheriting from `Food` with:
    - A string `dish = "Biryani"`
3. Define class `Restaurant` inheriting from `Dish` with:
    - A string `name = "Spice Kitchen"`
4. In `main()`:
    - Instantiate object `f3` of class `Restaurant`
    - Call `type()`
    - Print `f3.cuisine`, `f3.dish`, `f3.name`

### 4. Hierarchical Inheritance Algorithm:
1. Define class `Jeans` with:
    - A string array `type[3] = {"Bootcut", "Wide Leg", "Skinny"}`
    - A method `brand()` to print "H&M - &Denim"
2. Define classes `Bootcut`, `WL`, and `Skinny`, each inheriting from `Jeans`, with respective `color` attributes.
3. In `main()`:
    - Instantiate objects `j1` (Bootcut), `j2` (WL), `j3` (Skinny)
    - Call `brand()` for each
    - Print `type` and `color` for each object

## Conclusion:
In this study, we explored and implemented various types of inheritance: single, multiple, multilevel, and hierarchical inheritance.
```

This markdown version structures the information clearly and is ready for any documentation or presentation!
