# Fundamentals of programming

### Table of Contents

- [Variables](#Variables)
- [Data Structures](#Data-Structures)
- [Control Structures](#Control-Structures)
- [Object Oriented Programming](#Object-Oriented-Programming)
- [Data Structures](#Data-Structure-Operations)

## Variables

Variables are used to store(hold) information(Data/Value). Which can be referenced(used) and manipulated(changed) later in a computer program.

Variables are also known as properties of a Class.

```c++
int a; // Declaring a var
int b = 10; // Declaring and initializing a Variable
printf(b); // Refrenceing the Variable
b = 20; // Manipulating the Variable
```

#### Local Variables

Variables that are in scope within a specific part of the program (function, class).

#### Global Variables

Variables that are in scope for the duration of the program's execution. They can be accessed by any part of the program.

##### Example
---

```swift
let gProjectName : String = "Basics"; // Global

class Person{
    let aName : String = "Steve"; // Local
    init(){
        print(aName);
        print(gProjectName);
    }
}
```
---

## Data-Structures
A computer is a machine that manipulates the information(data) and Data structure is used to define how information(data) will be organized, manipulated and utlized.

Data structure is a way of organizing the data(s). and Not only data(s) but also their relationship with eachother.

Data structuring can be done in two ways:
1. **Dynamic Allocation**
This types of structures are created at run time. Their Size is Dynamic and allocated during the execution of program.

2. **Static Allocation**
This types of structure are of fixed size which is allocated during the compilation proccess.

### Linear Data structure

Data that is stored sequentially using memory locations.

#### Array
Array is sequential collection of information(data/item) of same type
#### Stack
#### Queue
#### Linked List

### Non-Linear Data Structure

Data which is not stored sequentially.

#### Tree
#### Graphs
#### Table
#### Sets

## Control-Structures
## Object-Oriented-Programming

# Data-Structure-Operations
- CRUD
- Searching (Filtering)
- Sorting
- Merging
- Mapping
- Travarsal
- Splitting
