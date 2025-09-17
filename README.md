# Overloading


##  Aim
To study and implement different overloading methods in C++:
- Operator Overloading  
- Constructor Overloading  
- Function Overloading  

---

##  Theory
Overloading in C++ is a type of **compile-time polymorphism** where functions or operators are given multiple definitions to handle different types or numbers of inputs. This improves **readability, reusability, and flexibility** of the code.  

###  Operator Overloading
- Operators can be redefined for user-defined data types.  
- Example: The `+` operator can be overloaded to add two objects (not just integers).  
- The `<<` and `>>` operators are overloaded in iostream for input/output.  

###  Constructor Overloading
- A class can have multiple constructors with different parameter lists.  
- This allows objects to be created in different ways: with default values, partial values, or full values.  
- It provides flexibility during object initialization.  

###  Function Overloading
- Functions with the same name can exist with different parameter types or counts.  
- The compiler chooses the correct function at compile-time based on the arguments passed.  
- Example: `int add(int, int)` and `double add(double, double)`.  

---

##  Algorithms  

### 1️ Operator Overloading (BankAccount)  
1. Create class with data member `balance`.  
2. Define constructor to initialize balance.  
3. Overload `+` operator to add balances.  
4. Display result.  

### 2️ Constructor Overloading (Ticket)  
1. Create class with members `movie`, `seat`, `price`.  
2. Define three constructors: default, one-parameter, three-parameter.  
3. Display ticket details.  

### 3 Function Overloading (Bill)  
1. Create class with functions `bill()` and `bill_taxed()`.  
2. Overload with `int` and `double` types.  
3. Display results.  

---

##  Conclusion
We studied three types of overloading in C++:  
- **Operator Overloading** → makes operators work with user-defined types.  
- **Constructor Overloading** → provides multiple ways to initialize objects.  
- **Function Overloading** → allows the same function name for different parameter sets.  

Overloading enhances **flexibility, code efficiency, and readability** in object-oriented programming.  
