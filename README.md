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

Arrays can be allocated both statically and dynamically.

A Single item of an array is called element. thus collection of elements of same type is called an Array.

##### One Dimensional Array
Array Containing the items of same types which can be access and stored at sinlge index.

**Example**
```swift
let anUserNames : [String] = ["Ramesh","Mahesh","Suresh"]; // This is an Array containing the User names... User names are of type string so we can say that 'anUserNames is an Array of Strings'.
```

##### Multi Dimensional Array
A Multi-dimensional array associates each of its elements with multiple indexes.
Multi Dimensional Array is also known as a table or matrix.
An Array of Array can be called multidimensional array.

**Example**
```swift
let player = [
       ["A", "B", "C", "D", "E"],
       ["F", "G", "H", "G", "M"],
       ["H", "I", "J", "K", "L"],
       ["M", "N", "O", "P", "Q"],
       ["R", "S", "T", "U", "V"]
    ]

for p in player {
    for value in p{
        print(value)
    }
}

//Printing the element from  row 3 and column 4
// Column = Vertical arrangement of items.
// Row = Horizontal arrangement of items
print(player[3][4])
//Output : Q
```
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
