## Learning C++

**Description:** To devlop my coding skills in c++ I began work on a small-scale project that would use previous coding knowledge but also integrate new concepts. I chose to develop my own Battleship game by breaking down its key functions and eventually code them in myself to have a fully operational system.

When selecting a project it had to meet particular requirements:

### 1. Can be designed offline.

This means that I wanted a project that would let me 'step back' and design a solution before I even began coding. My ability to analyse, design, test and evaluate a piece of work is just as important as my ability to code, which meant that I wanted something that would let me develop both skills.

### 2. Contains enums and structures.

Previously I had only used enumerations and structures on several occasions, but I believed I could improve my understanding and ability to implement them into my work. Battleship is a particularly good project for this as both the ships and players will have multiple layers of data, including names, ship sizes, positions and player boards.

For example
```c++
struct Ship
  ShipType Type
  int Shipsize
  ShipPosition Position
  ShipOrientation Orientation
}
```
Where ShipPostion, ShipType and ShipOrientation are declared enums.

### 3. Uses pointers and references.

Pointers and references are commonly used to store data and retrieve it, aiding in the transfer of information between functions. At the time of starting this project most of my coding experience was in python where they were not used, therefore I wanted a project that would contain lots of them to help me understand why are they were needed.

Example in practice:
```c++
string fruit = "apple";
string* fruitptr = &fruit
```
The * indicates that we are creating a pointer, using the memory address retrieved by using &.

### 4. Is fun to develop.

A project that was fun to develop and had multiple layers of complexity would help me focus and increase my motivation to learn.

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).
