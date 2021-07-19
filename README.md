# BigInteger

An Implementation of BigInteger Library in C++


## Purpose:

* If you code in C++, this place is for you. Did you ever get disturbed by limited range of integer in C++. That limit get over now. Here is header file of BigInteger for you. Now you can directly include it in your C++ program and can go much beyond the limits. By including this header, you can take integer of any length and can perform majoriy of commonly used operations on it.
* So, what are you waiting for? Just download the files and include it in code by header:-
    ```cpp
    #include "BigInteger.h"
    ```
* Open to improvements and suggestions.
* Rest documentation is written below.

## Documentation

### ClassName
* BigInteger

### Constructors

* **BigInteger()** --> Default Constructor. Itializes number to zero.
* **BigInteger(string s)** --> Takes a number string as parameter(with or without sign).
* **BigInteger(string s, bool sin)** --> Takes absolute value as string as sign true and false for -va and +ve number respectively.
* **BigInteger(int n)** --> Initialize object from a int

### Get-Set Functions

* **setNumber(string s)** --> Set the value of number to number string s(without sign).
* **getNumber()** --> Returns (const)referance to string of the number(without sign).
* **setSign(bool s)** --> Set sign of number to + and - by s being false and true repectively.
* **getSign()** --> Returns (const)referance to bool sign of number.
* **absolute()** --> Returns BigInteger object to absolute value of number.

### Operators

#### Arithematic Operators
##### Binary
* **operator <kbd>+</kbd>** --> Returns BigInteger objects representing addition of two BigInteger objects. `Addition`
* **operator <kbd>-</kbd>** --> Returns BigInteger objects representing subtraction of two BigInteger objects. `Subtraction`
* **operator <kbd>*</kbd>** --> Returns BigInteger objects representing multiplication of two BigInteger objects. `Multiplication`
* **operator <kbd>/</kbd>** --> Returns BigInteger objects representing division of two BigInteger objects. `Division`
  > :warning: **Denominator BigInteger object should be in range of long long**: Be very careful here!
* **operator <kbd>%</kbd>** --> Returns BigInteger objects representing modulus of two BigInteger objects. `Modulus`
  > :warning: **Denominator BigInteger object should be in range of long long**: Be very careful here!

##### Unary
* **operator <kbd>++</kbd>(Prefix)** --> Pre-Increment BigInteger object by 1. `Preincrement`
* **operator <kbd>++</kbd>(Postfix)** --> Post-Increment BigInteger object by 1. `Postincrement`
* **operator <kbd>--</kbd>(Prefix)** --> Pre-Decrement BigInteger object by 1. `Predecrement`
* **operator <kbd>--</kbd>(Postfix)** --> Post-Decrement BigInteger object by 1. `Postdecrement`
* **operator <kbd>-</kbd>** --> Negate number(Changes its sign) `Unary Minus`
