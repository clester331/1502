# CS1502 (Fall 2023)

## Lecture 1 - Introduction to CS1502 (28 August 2023) 

### Impossible Problems
* There are an infinite number of algorithms
  * Some have not been discovered or invented yet
* Not mathematical representation can be used to express all algorithms  
* **Computational Model** - used as a way to represent a set of algorithms
  * Finite Automata
    * Captures a subset of algorithms
  * Turing Machine
    * Captures all algorithms
   
### Problems That Take Too Long
* An **unrealistically solvable** problem are problems that are *technically* possible to solve but take too long to solve
  * Travelling Salesman problem - Find a route to visit 1000 cities with a distance *d*
    * There are 1000! possible routes (1000! = 4 x 10^2567)

### toString()
* Sigma(Σ) is a **non-empty finite set** of symblos/alphabets
  * Σ = {0, 1} or Σ = {a, b, c} or Σ = {a,... ,z}
* A string is a **finite sequence** of symbols over a Σ

#### Example
* epsilon (ε) = the empty string
* if s is a string, |s| is the length of string s
  * |01001| = 5
* A **language** is a **set** of strings
* The problem: determining whether a number is even
  * Is 72 Even? - Yes -> is 72
    * B = { x | x is even }     = {0, 2, 4, 6, 8, 10, ...}
      * Language = {"0","2", "4", ...} 
